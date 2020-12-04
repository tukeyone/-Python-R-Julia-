pipeline {
  agent any
  stages {
    stage('1') {
      steps {
        sh '''1 9 * * *  ./anaconda3/bin/python work/CangQiong/auto/edu_daily_data.py  >> work/CangQiong/auto/log/edu_daily_data.log 2>&1
'''
      }
    }

  }
}