# COVID-19 API
An API for current information about the COVID-19 virus (Novel Coronavirus Strain).

<br/>

# Endpoints
|  GET Request  | Output  |
| ------------ | ------------ |
|  https://covid-19.nigelvm.com/ | Frontend to display all information. |
|  https://covid-19.nigelvm.com/all | Returns all total cases, recovery, and deaths. |
|  https://covid-19.nigelvm.com/countries | Returns data of all countries that has COVID-19 |
|  https://covid-19.nigelvm.com/countries/{country-name} | Returns data of a specific country |

<br/>

# Docker
Create and run the API in a docker container
```bash
docker run -d --restart=unless-stopped -p 9119:9119 --name covid-19-api nigelmpofu/covid-19-api:latest
```

<br/>

# Frontend Samples
|  Global Info             |  Cases by Country  |
:-------------------------:|:-------------------------:
![](https://raw.githubusercontent.com/nigelmpofu/covid-19-api/master/screenshots/tab1.png)  |  ![](https://raw.githubusercontent.com/nigelmpofu/covid-19-api/master/screenshots/tab2.png)

<br/>

### Credit:
> Forked from [Javier Aviles](https://github.com/javieraviles/covidAPI)

### Data Source:
> https://www.worldometers.info/coronavirus/
