Project Prohora
Website frontend features:
Search bar and carousel animation:
The search bar on the Prohora website will allow to access information much more effectively. It enhances user experience by allowing quick access to specific information about flood zones, climate change, and gender equality. It enables localized searches for alerts, improves resource efficiency, and encourages user engagement. By empowering users to find the information they need, it fosters a proactive approach to managing climate risks and advocating for gender equality. The carousel animation will show alarming areas which are/maybe get effected by flood!

Home:
The home page of the Prohora website serves as a central hub, offering an overview of the project and easy navigation to various sections. With a user-friendly design, it ensures quick access to essential resources and features engaging content that encourages community involvement. Additionally, it provides updates and announcements, fostering a sense of connection and purpose among users as they engage with the mission of combating climate change and promoting gender equality.

Climate:
The climate section of the Prohora website could be highly useful for users in several ways:

Educational Resources: It provides information about climate change causes, impacts, and solutions, helping users understand the issues at hand.
Data and Analytics: Users can access relevant data and statistics on climate trends, fostering informed decision-making and awareness.
Local Insights: It may offer localized climate information, allowing users to understand specific risks and challenges in their area.
Actionable Tips: The section can include practical advice on how to reduce their carbon footprint and contribute to climate action in their communities.
Community Engagement: It can encourage users to participate in local initiatives, events, and discussions related to climate issues, fostering a sense of community.
Connection to Gender Issues: By linking climate change to gender equality, it highlights the disproportionate impacts on women and marginalized groups, raising awareness of social equity in climate action.
Overall, the climate section empowers users with knowledge, tools, and resources to actively engage in combating climate change.

Maps:
This section offers up-to-date information on floods occurring in various regions in Bangladesh, along with visual representations (using Maps representation) to provide comprehensive insights. For example it’ll provide water level status of predefined river areas. All information will be generated by using NASA whether api’s. And it will run scheduler for updating information (update in every 1 hours in case of flood and rainy monsoon, else it’ll update in every 6 hours). Furthermore, based on the information it’ll send a push notification to the IOT device and the alarm system will turn on.

Gender Equality:
The Prohora website engages with gender equality by featuring dedicated content on the topic, promoting awareness campaigns about the challenges faced by women and gender-diverse communities during climate events. It provides resources tailored to empower these groups, addresses the intersection of gender and climate issues, and encourages community involvement in discussions and initiatives. Additionally, it offers educational materials that highlight the importance of gender equality in climate action.

Help and Contact:
Will have all emergency contacts and a Chatbot in case of accessing website information much more efficiently. In addition from here all kinds of relief information and immediate contact with Prohora team can be done.

Website Backend features:
NASA Data Integration:
The backend utilizes APIs to fetch real-time data from NASA’s Earth Science datasets, including SMAP, TRMM, and GPM. This data is processed to identify potential flood zones.

IoT Device Integration:
Data from IoT devices, such as ultrasonic and water level sensors, is collected and analyzed to monitor changes in water levels and detect flooding events.

Flood Zone Data:
Real-time data about identified flood zones, alerts, and updates are stored and managed to ensure users receive the latest information.

SMS Alerts:
Upon flood detection, the backend triggers SMS alerts to nearby firefighting departments and NGOs using a third-party service

IOT Device:
GSM sim module:
Will be using gsm sim800L module(For Demonstrtion Purpose) to get push notifications from the website backend API. Also it’ll send sms messages to the fire fighter and local disaster management authority in case of flood.

ESP8266 microcontroller(For Demonstrtion Purpose We Used Arduino Uno R3):
This microcontroller will be the center processing unit of our IOT Alarm system.

Passive buzzer:
Passive buzzer will be used to control the alarm volume. As this kinds of buzzer can work with PWM pinout.

Water Sensor and Ultrasonic Senor:
This two sensors will monitor the water level rise and will provide information to the microcontroller.

3.7V, 5V rechargabel ION battery:
Main power supply for the IOT device.

Voltage regulator:
In case of stepping down the voltage for the microcontroller.

Inflatable boat and First aid:
An inflatable boat with first aid kits will be available if the flood hits the area as an immediate rescue.

Rural environment:
For demonstration purpose we are creating a dummy rural environment to show how the IOT device will works.

Mobile Application:
Dashboard-

Climate:
Same information as website.

Maps and Flood:
Map and list view of different water level areas. List view will provide extra information’s as well. Some graph view of water level information of the selected area of last 7 days.

Gender Equity:
The Prohora app is vital for gender equality by providing mobile access to timely alerts and resources, enabling quick responses to emergencies, offering essential information for gender-specific needs, fostering community support, empowering users with education on rights, and ensuring access to critical information offline. Together with the website, it forms a comprehensive support system for climate resilience and gender equality.

Alarming areas:
List of alarming areas with location and water level situation.

Help and Contact:
same as website.