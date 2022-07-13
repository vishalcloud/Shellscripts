# Shellscripts
Shell scripts that I created for various automation or day to day tasks

dockerImageRemoval.sh - Gets the image name from parameters, Checks for images pulled for that image name, excludes the tag:latest and the newest image pulled, and removes all other images. Created to cleanup the older docker images. 

Example usage :  .\dockerImageRemoval.sh vishal/hello-world
