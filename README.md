# HW-9
ReadMe file for Kieran, Quinn, and Ethan Project 9. 


#READ ME

**What the code does**

This program gets the wait times for future trains coming into the the blue line stations on the MBTA.

It calculates the average wait times between future trains.

It outputs a summary of the data, an interactive map, and a bar graph to compare inbound and outbound trains.

**To Run The Code**

Press run all on "The Code" drop down. Then press run on the visual output cell. Within the visual output cell is the visuals of the data.

**Adding the API Key**

API key should be set in the second code box where it is declared an enviromental variable. The api key is "6040494e00ec42568a483d2f943f31e7".

**Notes about the code**

Uptown is outbound and downtown is inbound. The visuals use in and out while the codes writes with up and down. Inbound is toward the city and up and down correlate with north and south.

The second code cell in the code section has our API key, which can be changed to your own.

**Issues and challenges**

We had trouble with the API returning non values, ensuring the average wait time wasn't affected by trains with canceled or undefined times.
