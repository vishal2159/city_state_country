# Cities-States-Country
Get all Cities, State, Country all over the world.

**Steps for Installation** : -

Install the package with

      npm i city-state-country --save
      
**Usage**

      var worldMapData = require('city-state-country');


### Supported Methods


**Get list of all Countries**
      
     const countriesList = worldMapData.getAllCountries();

**Search Country**
      
     const countriesList = worldMapData.searchCountry('In');

**Get list of all States from a Country**
      
     const statesList = worldMapData.getAllStatesFromCountry('India');

**Get list of all States from World**
      
     const statesList = worldMapData.getAllStates();

**Search State details**
      
     const statesList = worldMapData.searchState('Maha');
     
It will return all states from world which starts with 'Maha'.

**Get list of all Cities from a State**
      
     const citiesList = worldMapData.getAllCitiesFromState('Maharashtra');

**Search City details**
      
     const citiesList = worldMapData.searchCity('Par');

It will return all cities from world which starts with 'Maha'.


**Submit Issues**

Email me regarding any issue me at vishal2159@gmail.com

**Note**

This database is taken from : https://github.com/hiiamrohit/Countries-States-Cities-database .<br/>
For any database related changes in plugin please write an email.
