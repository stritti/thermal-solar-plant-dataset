# Thermal Solar Plant Dataset

Realtime thermal solar plant dataset for machine learning.

I would like to provide reale time dataset of a thermal solar plant logged in 
the time of 2016-12-28 till 2018-10-10.

> Feel free to use data for research and development and let me know what you have learned and developed.



## Data Structure

Data is logged every minute but has some corrupted elements and data gaps.

The data is stored in individual CSV files. There is one log file per day. 
The log files are grouped in monthly folders.

The headers of the CSV files are in German and will be translated into 
English in the following. The temperature values are stored in Celcius.
Please consider that not all values are really provided with measured data.

### Dataset Header

Content of CSV files is structured in following columns:

| Column                         | Description                      |
|--------------------------------|----------------------------------|
| Datum & Uhrzeit                | date & time                      |
| Temperatur Sensor 1 [ °C]      | temperature of sensor 1 in °C    |
| Temperatur Sensor 2 [ °C]      | temperature of sensor 2 in °C    |
| Temperatur Sensor 3 [ °C]      | temperature of sensor 3 in °C    |
| Temperatur Sensor 4 [ °C]      | temperature of sensor 4 in °C    |
| Temperatur Sensor 5 [ °C]      | temperature of sensor 5 in °C    |
| Temperatur Sensor 6 [ °C]      | temperature of sensor 6 in °C    |
| Druck Sensor 7 [ Bar]          | pressure of sensor 7 [Bar]       |
| Temperatur Sensor 8 [ °C]      | temperature of sensor 8 in °C    |
| Durchfluss Sensor 9 [ l/h]     | Flow rate sensor 9 [ l/h]        |
| Durchfluss V40 [ l/h]          | Flow rate V40 [ l/h]             |
| Einheit                        | Unit                             |
| PWM 1 [ %]                     | ?                                |
| PWM 2 [ %]                     | ?                                |
| Drehzahl Relais 1 [ %]         | rotational speed relais 1 in %   |
| Drehzahl Relais 2 [ %]         | rotational speed relais 2 in %   |
| Drehzahl Relais 3 [ %]         | rotational speed relais 3 in %   |
| Drehzahl Relais 4 [ %]         | rotational speed relais 4 in %   |
| Betriebssekunden Relais 1 [ s] | operating seconds relais 1 [ s]  |
| Betriebssekunden Relais 2 [ s] | operating seconds relais 2 [ s]  |
| Betriebssekunden Relais 3 [ s] | operating seconds relais 3 [ s]  |
| Betriebssekunden Relais 4 [ s] | operating seconds relais 4 [ s]  |
| Fehlermaske                    | error mask                       |
| Statusmaske                    | status mask                      |
| Wärme [ Wh]                    | heat energy                      |
| Version                        | version                          |
| Systemzeit                     | system time                      |
| Systemdatum                    | system date                      |

# License

[LICENSE](LICENSE)

---

# Further Datasets

* Awesome Public Datasets: [https://github.com/awesomedata/apd-core], [https://github.com/awesomedata/awesome-public-datasets] 
* 25 Datasets for Deep Learning in IoT: [https://hub.packtpub.com/25-datasets-deep-learning-iot]
* MACHINE LEARNING DATASETS: [https://www.kaggle.com/pitasr/datasets]
* Great IoT, Sensor and other Data Sets Repositories: [https://www.datasciencecentral.com/profiles/blogs/great-sensor-datasets-to-prepare-your-next-career-move-in-iot-int]

