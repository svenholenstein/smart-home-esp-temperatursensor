# smart-home-esp-temperatursensor

## Funktionsbeschreibung
Ein ESP8266 wird verwendet um die Temperatur sowie Luftfeuchtigkeit zu messen. 
Am ESP ist ein kleines Display verbaut, um die gemessenen Informationen 
anzuzeigen. Dabei werden verschiedene Seiten auf dem Display erstellt, welche in 
einem Intervall der Reihe nach abgewechselt werden. Mithilfe verschiedener Icons
wird der Zustand der Luftfeuchtigkeit/Temperatur angezeigt (schlecht, gut, sehr gut).
<br><br>
Auf einem Raspberry Pi wird die Smart-Home Lösung Home Assistant aufgesetzt.
Mithilfe eines Dashboards werden die gemessenen Daten vom ESP ausgelesen und 
auf dem Dashboard benutzerfreundlich angezeigt. Das Dashboard kann über das
lokale-Heimnetzwerk im Web erreicht werden. Der ESP wird über Home Assistant 
mit dem Add-On ESPHome aufgesetzt und konfiguriert.

## HA-Dashboard
![HA-Dashboard view](https://github.com/svenholenstein/smart-home-esp-temperatursensor/blob/main/web-dashboard.png)
