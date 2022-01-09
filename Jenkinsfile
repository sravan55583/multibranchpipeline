pipeline{
agent any
stages{

stage("Branch"){
steps{
echo 'This is master Branch . . .'
}
}
stage("SCM"){
steps{
echo 'This is SCM stage'
}
}

stage("BUILD"){
steps{
echo 'This is Build stage'
}
}

stage("SonarScanner"){
steps{
echo 'This is Scanner stage'
}
}
stage("SonarQG"){
steps{
echo 'This is QG stage'
}
}
stage("Nexus"){
steps{
echo 'This is Nexus stage'
}
}
stage("Deploy"){
steps{
echo 'This is Deploy stage'
}
}
}
}
