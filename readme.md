Install nodejs :   
https://nodejs.org/en/download/
 
Download MagicMirror
https://github.com/MichMich/MagicMirror
 
Unzip MagicMirror
 
Run "cmd"
 
cd MagicMirror
 
npm install

cd vendor

npm install

cd ..

cd fonts

npm install

cd ..
 
cd config
 
copy config.js.sample config.js
 
notepad config.js
ctrl-f : YOUR_OPENWEATHER_API_KEY
 
get your key from https://home.openweathermap.org/api_keys
 
Copy&Paste your key to YOUR_OPENWEATHER_API_KEY
 
Install 7-zip : https://www.7-zip.org/
 
Download ttp://bulk.openweathermap.org/sample/city.list.json.gz
 
Unzip the gz file and find your city
 
 Change the name of location and insert the location ID
location: "New York",
locationID: "",  //ID from 
 
 
cd ..
 
node serveronly
 
Run chrome
 
Enter localhost:8080