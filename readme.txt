Simple Google Maps API  Javascript Sample
using Places and Geometry API


-click on the map to show nearby food places with region marked.

-To edit locations, type of place or radius; in the code,

change location by changing,
pyrmont = new google.maps.LatLng(lat,lng);


change radius and nearby place types from here,

var request = {
    location: pyrmont,
    radius: '500',
    types: ['food']
  };


Please report any errors or obsolete code due to API releases etc.