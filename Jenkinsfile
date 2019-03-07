node {
  checkout([
    $class: 'GitSCM',
    branches: [[name: '*/master']],
    doGenerateSubmoduleConfigurations: false,
    extensions: [],
    submoduleCfg: [],
    userRemoteConfigs: [[url: 'https://github.com/rkusmierek/jenkins-seed.git']]
  ])
  jobDsl (removedConfigFilesAction: 'DELETE', removedJobAction: 'DISABLE', removedViewAction: 'DELETE', sandbox: true, targets: 'Jenkinsfile')
}