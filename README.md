# Weather-App
Weather App using Java

Using open weather map api.

 

Please add this line in your build.gradle file

buildTypes.each {
it.buildConfigField 'String', 'OPEN_WEATHER_MAP_API_KEY', "/"abcdefg0123456/""
}


Add this syntax to
[USER_HOME]/.gradle/gradle.properties

MyOpenWeatherMapApiKey="<UNIQUE_API_KEY">
