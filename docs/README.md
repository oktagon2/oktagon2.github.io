# Headline

## GitHub

### Mit VS Code
* Am besten zuerst auf https://github.com/ ein Repository erstellen und dieses dann mit VS Code klonen. Dazu in VS Code "Close Folder" ausführen und dann im Register "Getting Started" auf "Clone Git Repository..." klicken. Das ausgewählte Repository wird dann in einem Unterordner des ausgewählten Ordners erstellt. Zusätzlich wird auch Git initialisiert und die Verbindung zu GitHub korrekt erstellt.
* Wenn bereits ein VS Code Projekt (resp. Ordner) besteht, dann kann man auch nachträglich auf https://github.com/ ein Repository erstellen und dann mit folgenden Befehlen (test1 ersetzen!) eine Verbindung zum GitHub Repository erstellen und den Quellcode pushen.
git remote add origin https://github.com/oktagon2/test1.git
git branch -M main
git push -u origin main 

## Heizen in der Übergangszeit

### Facts
* die Temperatur schwankt z.B. zwischen 11 und 20 Grad
* die Durchschnittstemperatur ist also 15.5 Grad
* die wärmsten 12 Stunden (von 10:00 Uhr bis 22:00 Uhr) sind über durchschnittlich warm.
* die wärmsten 12 Stunden sind durchschnittlich 18 Grad warm
* für eine Temperatur von 22 Grad brauche ich z.B. 7 Grad mehr als der Durchschnitt.

### Fazit
* die Rücklauftemperatur müsste also 24 Stunden lang 29 Grad (= 2 * 22 - 15) betragen
* oder 12 Stunden lang 36 Grad betragen. 
* (36 - 18) / 2 = 9
* Ich muss also die 18 Grad 9 Grad überheizen und die Heizung auf 27 Grad stellen
* Relative Heizenergie Variante 12 Stunden heizen: 12 * 9 = 108. 
* Relative Heizenergie Variange 24 Stunden heizen: 24 * 7 = 168. 
* Einsparung rund 35%!
* Die Heizung muss man grob auf 44 - Durchschnittstemperatur einstellen
* Die Absenkung um 15 Grad von 22:00 Uhr bis 10:00 Uhr.



