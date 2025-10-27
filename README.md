# WindTracker.online

**Track live wind observations from weather stations around the globe.**

WindTracker.online aggregates data from various **Open Datas** provided by different national weather services. Please note that data availability, update intervals, and station coverage vary widely between countries.

## Countris we have so far
🇦🇺 Australia
🇦🇹 Austria
🇧🇷 Brazil
🇭🇷 Croatia
🇩🇰 Denmark
🇪🇪 Estonia
🇫🇮 Finland
🇫🇷 France
🇩🇪 Germany
🇮🇪 Ireland
🇱🇹 Lithuania
🇳🇱 Netherlands
🇳🇴 Norway
🇵🇱 Poland
🇵🇹 Portugal
🇸🇮 Slovenia
🇪🇸 Spain
🇰🇷 South Korea
🇸🇪 Sweden
🇨🇭 Switzerland
🇹🇼 Taiwan
🇺🇸 **US coastal areas and islands

## Contribution & Feedback

While the application's code isn't hosted here, this GitHub repository is the central hub for: discussions, feature requests, and bug reports.

**[Share your ideas or report an issue!](https://github.com/t3brightside/windtracker.online/issues)**

### Add a New Country / Data Source

Want to expand coverage? We welcome **Python scripts** that can pull new data! The script should retrieve the latest observations, including station locations, and write the data to a **JSON file** matching the structure below.

```json
{
    "resolution_minutes": 60,
    "stations": [
        {
            "name": "Station Name",
            "longitude": 25.54916,
            "latitude": 60.30373,
            "precipitations": 0.1,
            "airtemperature": 8.9,
            "winddirection": 158.0,
            "windspeed": 8.6,
            "windspeedmax": 10.2
        }
    ]
}
```

## Disclaimer and Support

**Data Accuracy & Reliability:** Due to the nature of relying on third-party public APIs (which are not 100% reliable and tend to change), there is no warranty on data accuracy or app functionality whatsoever.

**This is a passion project;** tracking API changes, fixing issues, and developing new features can be time-consuming. Therefore, fixes and updates may not be immediate.

**Want to support development?** You'll find a donation button in the app's main menu. It would be a great inspiration to take the project further!

## Access the App
**[WindTracker.online](https://WindTracker.online)**
<br><br><br><br>
Instagram [@windtracker.online](https://www.instagram.com/windtracker.online/) for new country and feature updates. 
