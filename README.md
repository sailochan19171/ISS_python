This application describes about how to track the current location of International Space Station and maps the location.The script or set of code which we will write that will display the current location of ISS along with available crew names.It takes the value from the website  for every 5seconds and then updates the value of longitude and latitude thus which moves ISS icon on world map.It basically works on API,it takes current location of ISS in the form of latitude and logitude and locates value on to the map.

//import keyword is used to install packages from the predefined modules and import is a dynamic keyword
Modules 
1.import json
2.import webbrowser
3.import urllib.request



//API will provide with the current location of ISS in earth's orbit//
raw_data = url_req.urlopen("http://api.open-notify.org/astros.json")


urlib.request.urlopen()
//This function is used for inorder to open the API url.

json.loads(.read())
//This function is used for to read the data from the url.
