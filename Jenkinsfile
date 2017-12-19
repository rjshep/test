node {

    stage('checkout') {

      dir('test') {
        git poll: true, url: 'https://github.com/rjsheo/test.git', branch: 'master'
        git_commit = sh(returnStdout: true, script: "git rev-parse HEAD").trim()
      }

    }
}
