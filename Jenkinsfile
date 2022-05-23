#!/usr/bin/env groovy

pipeline {
    agent any

        stage('Terraform Init') {
            steps{
                sh label: '', script 'terraform init'
            }
        }
        stage('Terraform Plan') {
            steps{
                sh label: '', script 'terraform Plan'
            }
        }
        stage('Terraform Apply') {
            steps{
                sh label: '', script 'terraform Apply'
            }
        }
    }
}

