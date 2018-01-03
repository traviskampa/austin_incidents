# austin_incidents
D2008,D2009, D2010, D2011, D2016.txt are incidents data files collected by years, hosted in Kaggle. 
Their fields are :  "UID","ADDR","ADDRID","DES","DESID","TDATE","TTIME","LAT","LON","ICD"
which are : unique id, address, address id, incident description, description id, date, time, lattitude, longitude, incident id provided by police.

NBHood.txt is geographic data related to Austin Texas neighborhoods.
It has fields : "NBH_ID","NBH_NAME","POPULATION","WHITE_PC","AFRICA_PC","HIS_PC","ASIAN_PC","OTHER_PC","DENSITY","DEN_RANK","ACRES","Y"
The field with _PC means percentage.
The field DEN_RANK means density rank.
The field ACRES means size in acres.
The field Y shows that all records are collected in 2010.

STSUFFIX.txt is street suffix

U_ADDRS_XY:  unique address with coordianates
It has fields : "ADDRID","ADDR","LAT","LON","ZIPCODE","COUNTY","NBH_NAME","FMTADDR","LOCTYPE","STSUFFIX"
which are address id, address, latitude, longitude, zip code, county, neighborhood name, formated address, location type and street address.
Loctype and stsuffix are array fields.


 
