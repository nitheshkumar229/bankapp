node{
stage('scm checkout'){
git 'https://github.com/nitheshkumar229/bankapp'
}
stage ('compile-package'){
  def mvnhome= tool name: 'maven', type: 'maven'
  sh "{mvnhome}/bin/mvn package"
}
}
