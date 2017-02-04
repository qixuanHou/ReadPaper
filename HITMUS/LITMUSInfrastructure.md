#Detection of Damage and Failure Events of Critical Public Infrastructure using Social Sensor Big Data


##Summary

The paper demonstrates using social sensor big data to detect failure events or damages in critical infrastructures which lack continuous physical sensor monitoring. 

The system is built on LITMUS and targets for transpiration (bridges and highways) and energy (gas lines and power). The system proves the flexibility of LITMUS. Even without physical sensors, LITMUS produces a good result for a totally different topics. The system for detect failure in public infrastructures proposed in the paper only modifies LITMUS’s original search words and stop words and removes physical sensor feeds and produces impressive accurate rate of reporting damages in bridges, highways, gas lines and power.

However, the system also requires to identify the events first and then choose the search keywords and stop words for each event. For example, the paper mentioned four events, damages of bridges, highways, gas lines and power. Search terms identified for bridges, collapsed, damaged, and flooded, are bridge and stop words are friendship, reopened, pending, fish, bid, and wheelchair; search terms identified for highways are highway, snow, closed, blocked and accident and stop words are boating, watch, explore and delays. However, I am wondering whether there is an approach to collect data from Twitter with explicit keywords for specific events. I want my system to aim for general emergencies which requires healthcare. It is really hard to identify a entire list of events and then search for keywords and stop words for each event. 






##Link

https://grait-dm.gatech.edu/wp-content/uploads/2016/05/IoTBD_2016.pdf 

##Reference

Tien, I., Musaev, A., Benas, D., Ghadi, A., Goodman, S., & Pu, C. (2016). Detection of Damage and Failure Events of Critical Public Infrastructure using Social Sensor Big Data. Proceedings of the International Conference on Internet of Things and Big Data. doi:10.5220/0005932104350440
