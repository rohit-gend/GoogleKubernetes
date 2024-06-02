Deploy to Kubernetes in Google Cloud


# Update project in Jenkinsfile

sed -i "s/YOUR_PROJECT/$GOOGLE_CLOUD_PROJECT/g" Jenkinsfile
git config --global user.email "student@edu.com"     <------ put from first consol 
git config --global user.name "student"               <--------- from login status
git add .
git commit -m "built pipeline init"
git push
