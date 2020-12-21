This website displays a map highlighting a lot of locations for a café chain. Users can find a store location by typing the zip code in the search bar, then the map will zoom in to show the stores around the zip code that users just typed. Users can also scroll through the list of stores to find the specific information about the store that they really want to go. In this project, I used web technology including Google Maps JavaScript API, NodeJS for API, MongoDB Atlas for Database and Google Maps Geocoder to geocode users zip code.


Technical Requirements
Use Google Maps JavaScript API
https://developers.google.com/maps/documentation/javascript/tutorial
Use NodeJS for API 
Use MongoDB Atlas for Database
Use Google Maps Geocoder to geocode users zip code
https://developers.google.com/maps/documentation/geocoding/start
API Endpoints



# Google Maps App

## Requirements

1. Retrieve your own Google Maps API Key (it is free)

    https://developers.google.com/maps/documentation/javascript/get-api-key?utm_source=google&utm_medium=cpc&utm_campaign=FY20-Q3-global-demandgen-displayonnetworkhouseads-cs-GMP_maps_contactsal_saf_v2&utm_content=text-ad-none-none-DEV_c-CRE_460848633529-ADGP_Hybrid%20%7C%20AW%20SEM%20%7C%20BKWS%20~%20Google%20Maps%20API%20Key-KWID_43700035216023629-kwd-298247230705-userloc_9067609&utm_term=KW_google%20maps%20api%20key-ST_google%20maps%20api%20key&gclid=Cj0KCQiAifz-BRDjARIsAEElyGJsLQ9jOfSlkyUUzamn7zpSJniBgtwmN7bXWXcjUearkxsrCQQ1hDgaAhwNEALw_wcB

2. Add your API Key to Google Maps link in `index.html`:
````
src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap">
````
Replace `YOUR_API_KEY` in the url with the API Key you retrieved using the tutotial above.


