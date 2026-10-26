pipeline {
    agent any

    stages {
        stage('环境信息') {
            steps {
                echo "======================================"
                echo "当前正在构建的分支是: ${env.BRANCH_NAME}"
                echo "当前代码提交版本是: ${env.GIT_COMMIT}"
                echo "======================================"
            }
        }
        
        stage('模拟测试') {
            steps {
                echo "正在对 ${env.BRANCH_NAME} 分支进行模拟测试..."
                echo "测试通过！"
            }
        }
    }
}
