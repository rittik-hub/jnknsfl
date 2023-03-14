pipeline {
  agent any
  environment
  {
    NEW_VERSION= '1.3.0'
  }
  stages  {
    stage("build")
    {
      steps
      {
        echo 'Build phase'
        echo "Building version ${NEW_VERSION}"
      }
    }
    
    stage("test")
    {
      steps
      {
        echo 'Test phase'
      }
    }
    
    stage("deploy")
    {
      steps
      {
        echo 'Deploy phase'
      }
    }
  }
}
