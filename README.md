SmartCan
========

Spark-Connected Garbage Can


Assumptions + Ideas → Product

WHAT IS SMARTCAN? WHAT IS OUR CAUSE?
========
Tired of carrying a heavy garbage can and always ripping it? Missing your opportunity to take the trash out at the right time? It is easy to ignore the mundane task of dumping the garbage as it fills up. When attempting to close the bag, the bag rips. Now your garbage is all over the ground. Introducing the first residential smart garbage can! The "SmartCan" is a cloud-connected garbage can that informs you of when it is the perfect time to take out your trash.

DESIGN PROCESS - MATERIALS AND RESOURCES USED:
========
The SmartCan comes with sensors installed to report your trashcan's current height and weight directly to YOU, the user. It automatically connects to your smartphone through our app to keep you updated. Based on your settings, you can choose whether you want to be notified once a day, or only if the height or weight exceeds a fixed level. That means no more late night panicking when it's time to dump the garbage. There are also plans to add built-in aeorsol dispensers throughout the entire height of the can, so your trash will never smell!

SENSORS
========
FSR 406 Weight/Force Sensor: http://www.interlinkelectronics.com
Sharp GP2Y0A21YK Infrared Proximity Sensor 10-80cm: https://www.sparkfun.com/products/242
                                    OR
Sharp GP2D120XJ00F Analog Distance Sensor 4-30cm: http://www.pololu.com/product/1136




Progress: So far, we have acquired a digital scale, an infrared distance sensor, and a spark core. This will enable us to measure the weight of the scale and the height of the garbage and send the information to the cloud.  We have connected the spark core to the Internet, as well as have constructed the framework of a program that will run on the user's phone, which will take the information and notify users when the garbage weighs too much, or is full.  

Next Steps (Prototype): Our next steps on the technical side include connecting our peripheral devices to the spark core. This involves wiring the distance sensor into the circuit, and hacking into the digital scale’s load cell to connect it to our core. We then have to mock up a first physical model, and code the iOS app that will tie everything together.

Next Steps (Beta): Our next steps also require Beta Testing customers who are interested in our product. We will give people fliers, telling them to join our mailing list/beta if they are interested and want to learn more about our product. Once they are joined, the prospective customers will be split into three different groups. All groups will be given the same information about the product however, one group will be told the SmartCan is worth $25, another will be told it is worth $50 and the final group will be told it is worth $75. At the end of the testing, based on what the results are, we will base our final pricing and opinions on its effectiveness. Come speak to us regarding joining our beta to get more information about our product as the release date of January 1, 2015 comes near!

Extra Information We Did Not Have Time to Include in the Presentation (Progress/Previous Steps in More Depth): Up until now, we have done many things related to the project. After brainstorming ideas and coming up with a final invention, we got into our groups and then decided on our final plans about what we want to do with the SmartCan. We were then told about our $119.00 budget, which we decided to use in order to purchase our materials. My partners and I have gone to the drawing board and decided what it is we will need to implement the design and structure of our SmartCan. We have reached the decision to include one SHARP Distance Sensor, ranging from 4-30cm. This sensor will use reflected infrared light to measure the distance the garbage is away from the sensor. This is helpful in determining a good base limit as to where to garbage should stop being filled. The SHARP IR Sensor was received for free from Dino on the 6th floor. There is also a weight sensor that will be hacked to measure the weight of the garbage and then will send the data to the Spark Core. The Spark Core will then send a notification to your phone via cloud, telling you the bag is getting too heavy. The digital scale was $32.65. Finally, the Spark Core was purchased for $39.00. The Spark Core was programmed into our Wi-Fi, allowing access to begin using it to program our scale and IR sensor.  This still gives us enough money to be able to experiment with installing aerosol cans to keep the odor of the SmartCan very freshening. We will now work with the technicalities of designing the can after we beta test potential customers to decide what we will set our base price at, as long as it is more than what it takes for us to build the product.  
