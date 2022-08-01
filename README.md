

Stages
# 1. Initial
In first stage we need city API, to localize every city in the correct position
In page https://rapidapi.com/ we suscribe for free to https://rapidapi.com/wirefreethought/api/geodb-cities/ 
This going to be us API weather.
We have code sniped  Elect JS code. . .

Next, we need weather API
In https://home.openweathermap.org/ we go to account My Services  API keys
And copy key

## 2. Create app, extensions
#### npx create-react-app react-weather-app
créate-react-app  to create the aplication with all modules we need
react-weather-app  name

The next we going to install is 

### react-accessible-accordion
‘React Component for creating an 'Accordion' that adheres to the WAI ARIA spec for accessibility.’ Say the oficial document.
Expanding multiple items at once: If you set allowMultipleExpanded to true then the accordion will permit multiple items to be expanded at once.
### react-select-async-paginate
AsyncPaginate is an alternative of Async but supports loading page by page. It is wrapper above default react-select thus it accepts all props of default Select

## 3. Code
We going to create 5 (five) files (with a css for each -less one).
### App.js
Concat all components, and add the logic for the correct function
### search.js
Component used to for make the search and concat with API 
### current-weather.js
The principal visual component for look daily weather
### forecast.js
For look weekend weather
### api.js
Save & export APIs


# Special thank's
To all professors in freeCodeCamp for the excelent step to step class.

