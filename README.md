# UI-for-API
Cloud Homework3
# UI for API Services
GIT Repository for cloud Homework3-Developed an UI in javascript for the API that provides weather forecast information.
<p>a.The UI takes the date as an input and provides the forecast for the next five days.
<p>b.The UI uses an third party weather API and returns the forecast for next five days

<b><u>Environment Setup:</b></u>
<p><b>To install Django in AWS ubuntu instance follow these steps:</b>
<p>sudo apt-get install language-pack-en

enter - 'Y'

sudo locale-gen en_GB.UTF-8

sudo -i

apt update

apt install -y  python3-dev python3-setuptools python3-pip

pip3 install Django

pip3 install django-import-export ( not required since data is already in the db )

pip3 install djangorestframework


<b>Description:</b>
<p>The API services are generated for the following methods </p>
<p>GET METHOD -Forecast/{date}- It returns the forecast for 5 days in future from the specified date the data is retrived from the database</p>
<p>GET METHOD -externalapi - It returns the forecast for 5 days in future from the current date the data is retrieved from third party API </p> 


<b>How to use these API</b>
<p>FORECAST/date can be called using:base_url/forecast/date</p>
<p>external API can be called using:base_url/externalapi
