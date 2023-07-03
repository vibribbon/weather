# weather
A small weather RSS reader

On linux place into /user/local/bin/ and change permissions as follows: 
sudo chown root /user/local/bin/weather.sh 
sudo chmod 755 /user/local/bin/weather.sh

Dependancies: aria2 sudo apt-get install aria2

This app will present a 3 day forecast for the locaiton you select (London by default).  Change the code number at the end of the https://weather-broker-cdn.api.bbci.co.uk/en/forecast/rss/3day/2643743 string to a location of your choice (2643743 = London,UK).  Go to https://www.bbc.co.uk/weather/ and the location you search for will appear at the end of the address bar.

END
