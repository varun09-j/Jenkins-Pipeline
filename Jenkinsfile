pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo "Building the code using Maven to compile and package"
                echo "Tool: Maven"
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo "Running unit tests to ensure code functions as expected"
                echo "Running integration tests to ensure components work together"
                echo "Tools: JUnit, TestNG"
            }
        }

        stage('Code Analysis') {
            steps {
                echo "Analysing code to ensure it meets industry standards"
                echo "Tool: SonarQube"
            }
        }

        stage('Security Scan') {
            steps {
                echo "Performing security scan to identify vulnerabilities"
                echo "Tool: OWASP Dependency Check"
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo "Deploying application to staging server"
                echo "Tool: AWS EC2"
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo "Running integration tests on staging environment"
                echo "Tool: Selenium"
            }
        }

        stage('Deploy to Production') {
            steps {
                echo "Deploying application to production server"
                echo "Tool: AWS EC2"
            }
        }

    }
}
