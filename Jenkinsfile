node {
    stage('build'){
        echo "building"
    }
}
stage('Deploy approval'){
    input "Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "deploying"
    }
}
node {
    stage('deploy to qa'){
        echo "testing"
    }
}
stage('Testing Approval'){
    input "Happy Yes? No?"
