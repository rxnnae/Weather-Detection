<h1><p align="center">
  Weather Detection System
</p></h1>

<h5>An IOT- based hardware system capable of detecting the weather changes from various sensor readings. Read on for the details!</h5>

<h2>Introduction</h2>
<p>The weather monitoring system plays a large utility in varied areas from agricultural growth and development to industrial development. Sensing the weather has been important to man over the centuries. The winds and other weather variables are of equal concern and can have an even greater impact on our modern, high-tech lifestyle. A weather station is that facility on land or sea, which has instruments and devices for observing and measuring atmospheric parameters to provide the information for weather forecasts. Modern weather monitoring systems and networks are designed to make the measurements necessary to track these movements in a cost-effective manner.</p>
<h2>Project Requirements</h2>
<h3>Hardware Requirements</h3>
<ul>
  <li>DHT11- Digital Humidity and Temperature Sensor</li>
  <li>KG004 - Rain Detection Sensor</li>
  <li>ESP8266 - NodeMCU board</li>
  <li>Connecting Wires</li>
  <li>Bread board</li>
</ul>
<h3>Software Requirements</h3>
<ul>
  <li>Arduino IDE </li>
  <li>ThingSpeak Cloud</li>
</ul>
<h2>Features</h2>
<ul>
<li>Data from the sensors may also be sent to a web page that is accessible from any location in the world.</li>
<li>Because there are fewer parts, the smart weather monitoring system's maintenance costs are also quite low.</li>
<li>The Smart Weather Monitoring System's sensors collect and analyze data that is used to accurately predict the weather.</li>
<li>These Sensors Can Easily Detect Any Sudden Change in The Forecast Because Of Their High Speed.</li>
<li>In the case of a smart weather monitoring system, a prior warning of the weather conditions is also possible. Visit a website for an IoT portal to quickly see this prior alert.</li>
<li>When compared to traditional weather monitoring systems, the smart weather monitoring system is quite compact and simple to install.</li>
<li>Smart Weather Monitoring Systems Have Very Low Power Requirements.</li>
<li>The Smart Weather Monitoring System's use of much less expensive sensors makes this project very cost-effective.</li>
</ul>
<h2>Results</h2>
<p>With this project we were successful in making a small-scale weather station that would be able to generate and visualize the local surrounding environmental conditions such as temperature, humidity and rain. The data is stored on cloud and the visualization for the same is carried out in cloud as well.</p>
<p>We first began by carrying out a simulation of the circuit in TinkerCad, a free web app for 3D design, electronics, and coding.</p>
<p align="center"><img src= "https://github.com/rxnnae/Weather-Detection/blob/main/Images/simulation.png" width="300" ><br><i>Fig. Picture of the simulated circuit</i></p>
<p>We then connected the components of the circuit together in a 400-point bread-board, and ran the blinker tests on the Arduino IDE to check if the NodeMCU board was working correctly. The code for the weather station was then uploaded to the board. </p>
<p align="center"><img src= "https://github.com/rxnnae/Weather-Detection/blob/main/Images/Circuit.jpg" width="300" ><br><i>Fig. Picture of the implemented circuit</i></p>
<p>Once the sensor is successfully calibrated, the Arduino board begins its readings and the data gets sent to the ThingSpeak cloud. 
The temperature is measured in Celsius, while the humidity is measured in Relative Humidity (RH). The rain drop sensor either gives a high (rain detected) or a low (rain not detected) value. 
We can see here that the readings are taken every millisecond, to ensure more accurate plotting and readings. 
</p>
<p align="center"><img src= "https://github.com/rxnnae/Weather-Detection/blob/main/Images/ArduinoIDE.png" width="650" ><br><i>Fig. Serial Monitor output in Arduino IDE</i></p>
<p>Once the data is read, it is aggregated in the ThingSpeak cloud, which is used to plot graphs of temperature, humidity and rain detection over time. </p>
<p align="center"><img src= "https://github.com/rxnnae/Weather-Detection/blob/main/Images/RT_output.png" width="650" ><br><i>Fig. Real-time output on ThingSpeak</i></p>
<h2>Conclusion</h2>
<p>This project aims to measure the various parameters like temperature, humidity and rainfall and continuously monitor them. The data can be stored online which can be used to forecast weather and eventually analyze climate patterns as well as for other meteorological purposes. The system uses a good combination of analog and digital sensors in wired and wireless modes of operation. This system can be used by farmers and agriculturists to monitor the weather conditions in their area, as it is cheap and lightweight in nature, and also provides a graphical representation of the data for easier visualization.</p>
<h2>Future Work</h2>
<p>We can also add an SMS feature to indicate to the user if it is about to rain, and the current conditions outside should make it turn unsafe for them. 
In the future, this model can be used as a basis for a weather prediction model using Artificial Intelligence and Machine Learning models. 
</p>



