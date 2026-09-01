# DTM
## EP 01...
### Vorteile und Nachteile der Methode

ewrer
### Wie wurde die Methode umgesetzt
erwer

Bild
## EP.01 | Kleines Einmaleins der thematischen Kartographie | Dasymetrische Choroplethenkarte
### Arbeitsaufgabe 01
Im Rahmen der ersten Arbeitsaufgabe wurden zum Thema „Die Bevölkerung Berlins 2025“ drei Karten in unterschiedlichen Darstellungsvarianten erstellt: eine absolute, eine relative und eine dasymetrische Darstellung. Bei allen drei Karten gibt die Farbgebung Auskunft über die Wertigkeit des Bezirks entsprechend der Legende. Zudem wurden die drei Karten in einem Layout vereint, um die Unterschiede der Varianten zu verdeutlichen. Die absolute Karte zeigt die Gesamteinwohnerzahl im jeweiligen Berliner Bezirk. Bei der relativen Karte werden die Einwohner pro km² dargestellt, wobei allerdings auch unbewohnte Flächen mitberechnet werden. Dies ist bei der dasymetrischen Karte nicht der Fall, diese zeigt ebenfalls die Einwohner pro km², schließt unbewohnte Areale jedoch aus und gibt somit die tatsächliche Einwohnerdichte wieder. So zeigt der Vergleich, wie unterschiedlich man eine Datengrundlage durch Karten interpretieren kann, wobei die dasymetrische Darstellung Fehldeutungen durch unbewohnte Areale, wie zum Beispiel Wälder oder Seen, vermeidet und somit das räumlich aussagekräftigste Bild der Bevölkerungsverteilung liefert.
<img width="3509" height="4963" alt="Bev_Berlin_2025" src="https://github.com/user-attachments/assets/2cbf022f-80d5-463d-bed9-b58150c3285d" />

## EP.02 | Kleines Einmaleins der thematischen Kartographie | Gitterchoroplethenkarten
### Arbeitsaufgabe 02
Für die zweite Arbeitsaufgabe wurde das Thema Gitterchoroplethenkarten anhand einer rasterbasierten Karte auf Grundlage eines Datensatzes über Kirschbäume in Berlin visualisiert. Um die räumliche Verteilung unabhängig von administrativen Grenzen darzustellen, wurden die einzelnen Standorte der Kirschbäume in einem 500m-Hexagongitter zusammengefasst. Hexagone ohne Baumbestand (Wert 0) wurden dabei aus der Darstellung entfernt. Die Farbgebung der verbleibenden Hexagone gibt entsprechend der Legende Auskunft über die absolute Anzahl der Kirschbäume pro Rasterzelle. Durch das gleichmäßige Gitter werden städtische Muster und Dichte-Hotspots präzise sichtbar gemacht, wobei die Methode fehlerhafte Interpretationen durch unterschiedlich große Verwaltungseinheiten vermeidet und somit ein räumlich vergleichbares Bild der Baumverteilung liefert.
<img width="1191" height="842" alt="KirschenHexagon" src="https://github.com/user-attachments/assets/068a3771-6d44-4312-8ae3-2af953b5c92a" />

## EP.03 | Punktrasterkarten
Die Arbeitsaufgaben 03 und 04 greifen das Grundkonzept der vorherigen Aufgabe auf und projizieren dieses auf eine Punktrasterkarte. Das Konzept wird dabei mit demselben Datensatz über Kirschbäume in Berlin visualisiert. In beiden Karten werden nahe beieinander liegende Kirschbäume in einem Punkt zusammengefasst. Je mehr Kirschbäume sich im jeweiligen Rasterfeld befinden, desto größer wird der Punkt dargestellt. Gleichzeitig gibt die Farbe des Punktes entsprechend der Legende Auskunft über die genaue Anzahl. Bei der Karte der Arbeitsaufgabe 03 wurde statt klassischer Punkte eine Kirschblüte als Symbol genutzt; das Grundprinzip ist jedoch identisch mit dem der Arbeitsaufgabe 04. Ein wesentlicher Vorteil dieser Punktdarstellung gegenüber den Hexagonen aus Aufgabe 02 ist das visuell leichtere Kartenbild, da der Hintergrund gut erkennbar bleibt und Dichtezentren durch die Kombination aus Punktgröße und Farbe sehr intuitiv wirken. Zudem werden auch hier verzerrte Interpretationen durch administrative Grenzen vermieden. Ein Nachteil besteht jedoch darin, dass keine geschlossenen Flächen dargestellt werden und sich sehr große Symbole bei hoher Dichte überschneiden können.
### Arbeitsaufgabe 03
<img width="921" height="759" alt="3 (1)" src="https://github.com/user-attachments/assets/c7c6df6a-48bd-4430-9f21-b387396768f2" />

### Arbeitsaufgabe 04
<img width="1191" height="842" alt="KirschenPunkte" src="https://github.com/user-attachments/assets/b2b1ec17-fcf0-43a0-9fb8-37be4d55d16a" />

## EP.04 | Value-By-Alpha Mapping
In Arbeitsaufgabe 05 wird das Verfahren des Value-By-Alpha Mappings am Beispiel der Ungarischen Parlamentswahlen 2026 dargestellt. Bei dieser Methodik werden zwei Variablen in einer Karte kombiniert: Die Farbe repräsentiert den jeweiligen Wahlsieger (Fidesz oder TISZA), während die Transparenz (Alpha-Kanal) als Gewichtung dient, um eine zweite Variable abzubilden. Hierbei zeigt die farbliche Sättigung, wie eindeutig der jeweilige Sieg im jeweiligen Wahlbezirk ausgefallen ist. Die Value-By-Alpha-Karte wurde durch zwei klassische Choroplethenkarten ergänzt, welche die einzelnen Gesamtstimmenanteile der Parteien Fidesz und TISZA darstellen, um beide Parteien direkt miteinander vergleichen zu können.
### Arbeitsaufgabe 05
<img width="4960" height="3507" alt="EP04 Arbeitsauftrag 05" src="https://github.com/user-attachments/assets/cc66b419-164c-4732-a68d-a0530bbccff0" />

## EP.05 | Ursprung-Ziel-Karten
Für das Thema der Ursprung-Ziel-Karten wurden zwei Darstellungen auf einer Globusprojektion erstellt. Die erste Karte beschäftigt sich mit den Fluchtbewegungen aus der Ukraine im Jahr 2025, während die zweite Karte dieses Konzept aufgreift und die Fluchtbewegungen aus Afghanistan im selben Jahr zeigt. Die Herkunftsländer Ukraine und Afghanistan bilden dabei jeweils den zentralen Ursprungspunkt der Bewegungen. Von diesen Zentren führen Verbindungslinien zu den jeweiligen Zielländern. Zusätzlich sind die Zielländer mit Punkten markiert, wobei die Farbgebung und Dicke der Linien und Punkte entsprechend der Legende die Anzahl der geflohenen Personen repräsentieren. Ein großer Vorteil dieser Methodik liegt darin, dass räumliche Bewegungsströme und globale Vernetzungen anschaulich und intuitiv dargestellt werden können. Ein Nachteil ist jedoch das visuelle Durcheinander, bei sehr vielen Zielorten überlagern sich die Linien stark um das Ursprungsland herum, wodurch einzelne Verbindungen unübersichtlich werden und genaue Zahlenwerte schwer abzulesen sind.
### Übungsbeispiel
<img width="3507" height="2480" alt="EP05 Ukraine" src="https://github.com/user-attachments/assets/9b18833f-1c76-481f-87e4-6c50afe8b8f2" />

### Arbeitsaufgabe Flüchtlingskonstellation
<img width="1437" height="1012" alt="EP05 Afghanistan" src="https://github.com/user-attachments/assets/8db5a28c-425d-448a-90db-efd2a7e50de9" />

## EP.06 | Tilemaps
Die folgenden Karten zum Thema Tilemaps zeigen das Höhenrelief Berlins (im Übungsbeispiel) sowie das Höhenrelief Deutschlands (in Arbeitsaufgabe 06) im Lego-Stil. Hierfür wurde die jeweilige Region mit einem gleichmäßigen Hexagongitter abgedeckt, wobei die einzelnen Kacheln durch Noppen mit der Beschriftung „BHT“ optisch wie Lego-Bausteine gestaltet wurden. Die Farbgebung der Hexagone gibt dabei entsprechend der Legende Auskunft über die durchschnittliche Höhe in Metern innerhalb des jeweiligen Rasterfeldes. Diese Karten zeichnen sich durch eine stark vereinfachte Visualisierung aus, welche komplexe Topografien intuitiv und ansprechend vermittelt. Durch das einheitliche Raster bleiben die Einheiten zudem räumlich perfekt vergleichbar. Diese starke Generalisierung macht die Karte zwar sehr anschaulich, führt jedoch dazu, dass feine Details wie einzelne Erhebungen oder Täler verloren gehen. Um solche Details abzubilden, wären sehr kleine Hexagone nötig, wodurch die Übersichtlichkeit verloren ginge. Dies macht die Methodik für präzise geografische Analysen ungeeignet.
### Übungsbeispiel
<img width="3507" height="2480" alt="EP06 Berlin" src="https://github.com/user-attachments/assets/dc8c016f-11bc-48ca-943a-ad4127efce90" />

### Arbeitsaufgabe 06
<img width="3507" height="4960" alt="EP06 Arbeitsaufgabe 06" src="https://github.com/user-attachments/assets/170e2a6c-e217-49e7-871f-8cfc8dfc3e05" />

## EP.07 | Animation in QGIS
Im Rahmen des Themas „Animationen in QGIS“ wurden zwei zeitdynamische Karten zur Visualisierung von Meteoritenschauern erstellt. Die erste Animation zeigt die Perseiden über Mitteleuropa am 12. und 13. August 2025 im Stundentakt. Die zweite Animation (Arbeitsaufgabe 07) bildet die Geminiden über Moldawien und Teilen der Ukraine am 13. Dezember 2025 in einer zeitlichen Auflösung im Minutentakt ab. Hierbei wurde der räumliche Ausschnitt gezielt eingegrenzt, um die Datenmenge zu reduzieren, da höhere Datenmenge zu technischen Problemen führte. Der große Vorteil von Kartenanimationen liegt in der anschaulichen Darstellung zeitlicher und räumlicher Dynamiken, so lassen sich Bewegungen und Richtungen der Sternschnuppen wesentlich intuitiver erfassen als in einer statischen Karte. Der Nachteil besteht jedoch im hohen Rechen- und Speicheraufwand sowie in der fehlenden dauerhaften Übersicht. So müssen Betrachter die Animation aufmerksam verfolgen, da Informationen im Zeitverlauf immer wieder auftauchen und verschwinden.
### Übungsbeispiel
<img width="1044" height="776" alt="EP07 Perseiden" src="https://github.com/user-attachments/assets/3d167fd6-e119-4f35-99ec-76b5900d40ea" />

### Arbeitsaufgabe 07
<img width="2243" height="1000" alt="EP07 Arbeitsaufgabe 07" src="https://github.com/user-attachments/assets/63398c84-23af-4866-8104-0abf16d28440" />

## EP.08 | Mesh-Daten
### Arbeitsaufgabe 08
<img width="1310" height="914" alt="TEST-ezgif com-gif-maker (1)" src="https://github.com/user-attachments/assets/bd020e03-4d22-4127-b4bb-23fa1c6f4624" />

## EP.09 | 3D-Geländemodelle
### Arbeitsaufgabe 09 2,5D
<img width="1790" height="1057" alt="EP09 Arbeitsaufgabe 09 1" src="https://github.com/user-attachments/assets/21623b30-38e9-4351-b639-7f1c8fa39fcb" />

### Arbeitsaufgabe 09 3D
<img width="2386" height="1175" alt="EP09 Arbeitsaufgabe 09 2" src="https://github.com/user-attachments/assets/e235411d-4998-4a85-8ea1-b1c35d7fde96" />
