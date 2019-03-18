#Bash script written to check if user is ready to upgrade and to execute the upgrade script
#Myla Fairchild

#!/bin/bash
n_option=“We'll try again tomorrow“
y_option=“Let’s get ready to upgraaaaade!”

echo “Ready to upgrade? Answer 1 for Yes or 2 for No.”
read upgrade_answer

if [ $upgrade_answer} -eq 2 ]
then
   echo $n_option
elif [ $upgrade_answer -eq 1 ]
then
    echo $y_option
    /bin/sh /path/to/the/other/script
else
    echo "Invalid input; aborting"
    exit 1
fi
