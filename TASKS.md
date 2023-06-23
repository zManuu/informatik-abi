## Tasks

[Level 1](#level-1)  
[Level 2](#level-2)  

## Level 1

***Nr. 1***

Erstelle eine Liste, die alle Zahlen von 10 bis 77 beinhaltet, gib diese Liste aus.

***Nr. 2***

Der Benutzer soll zwei Zahlen eingeben: `min` und `max`. Erstelle eine Liste, die von `min` bis `max` alle Zahlen beinhalten, gib diese Liste aus.

***Nr. 3***

Erstelle eine Liste wie nach Nr 2. Finde das Minimun und das Maximum der Liste und gebe die Werte wie folgt aus: `Liste: ... Min: ... Max: ...`

***Nr. 4***

Erstelle eine Liste wie in Nr. 2. Gib die Summe aller Zahlen aus sowie das Produkt aller Zahlen.

***Nr. 5***

Erstelle eine kleine Namensliste mit ca. 8 Vornamen. Gib eine zweite Liste aus, die alle Vornamen beinhaltet, die Länger als 5 Zeichen sind.
<details> 
  <summary>Tipp</summary>
   Um die Länge eines Strings zu bekommen, benutze len(string). Dies ist möglich, weil ein String gleichzeitig eine Liste von einzelnen Zeichen ist und man len(liste) machen kann.
</details>
<br>

## Level 2

***Nr. 6***

Erstelle eine Liste wie in Nr. 5. Gebe alle Namen aus, die mit b beginnen (B und b).
<details> 
  <summary>Tipp</summary>
   Hast du einen String, ist dieser gleichzeitig eine Liste aus Zeichen. Mit list[0] erhälst du das erste Element einer Liste, du kannst also string[0] nutzen, um den ersten Buchstaben zu vergleichen.
</details>
<br>

***Nr. 7***

Erstelle eine Liste wie bei Nr.5. Gebe alle Namen aus, die ein E im Namen haben.

***Nr. 8***

Erstelle eine Liste wie bei Nr.5. Gebe alle Namen aus, die ein E aber und kein A im Namen haben.

***Nr. 9***

Erstelle eine Liste wie in Nr. 5. Gebe die Summe der Längen der Namen aus.

***Nr. 10***

Lass den Benutzer Alter, Geburtsjahr und Gewicht eingeben. Berechne eine Statistik nach der folgenden Formel: Alter * (Geburtsjahr / Gewicht) + 10,5

<details>
  <summary>Tipp</summary>
   Beim Programmieren schreibt man Kommazahlen mit Punkt statt mit Komma. 10,5 muss also zu 10.5 geändert werden, damit die Formel berechnet werden kann.
</details>
<br>

## Level 3

***Nr. 11***

Eine Schlange klettert einen Brunnen hoch. Jeden Tag schafft sie 6 Meter. In der Nacht rutscht sie jedoch wieder 2 Meter hinunter. Gib Tage und Nächte aus, die die Schlange im Brunnen war. Die Brunnen-Tiefe soll der Benutzer eingeben können.

<details>
  <summary>Tipp</summary>
   Nutze eine While-Schleife
</details>
<br>

***Nr. 12***

Erstelle eine Liste aus Zufallszahlen zwischen 10 und 100 mit 50 Elementen. Die Elemente dürfen nicht doppelt vorkommen.

<details>
  <summary>Tipp</summary>
   Nutze eine While-Schleife
</details>
<br>

***Nr. 13***

Erstelle eine Funktion `roll` die eine Zahl zwischen 1 und 6 zurückgibt, wie ein Würfel. Simuliere 10 Runden, gib das jeweilige Ergebnis aus, den Durchschnitt und die Summe aller Runden.

***Nr. 14***

Erstelle eine Funktion `sign`, die als Parameter eine String-Liste übernimmt. Modifiziere die übergebene Liste so, dass an jedes Element das Zeichen `✔` angefügt wird.

***Nr. 15***

Erstelle eine Funktion `printList`, die als Parameter eine Liste übernimmt. Geb die Elemente in folgendem Format wieder:
```
- element 1
- element 2
- ...
```

## Level 4

***Nr. 16***

Erstelle eine Funktion `encrypt`, die als Parameter einen String und eine Zahl übernimmt. Verschlüssle den übergebenen String mit dem Caesar-Chiffre und gib ihn zurück.

<details>
  <summary>Tipp</summary>
    Um den ASCII-Wert eines Zeichens zu bekommen, kannst du in Python ord(zeichen) benutzen. Diese Zahl kannst du addieren. Um von einer Zahl zwischen 1 und 256 das zugehörige ASCII-Zeichen zu bekommen, benutze chr(zahl)
</details>
<br>

***Nr. 17***

Erstelle eine Funktion `decrypt`, die die Funktion in Nr. 16 rückgänig macht.

***Nr. 18***

Erstelle eine Funktion `encrypt2`, die zwei Strings übernimmt und das Vignère-Chiffre anwendet. Schreibe auch eine zugehörige Funktion `decrypt2`.

***Nr. 19***

Erstelle eine Funktion `createPassword`. Der Benutzer gibt die Länge des Passworts an. Passwörter sollen alle ASCII-Zeichen beinhalten.

***Nr. 20***

Erstelle eine Funktion `createUUID`. Eine UUID sieht wie folgt aus:  
`9b1deb4d-3b7d-4bad-9bdd-2b0d7b3dcb6d`  
`1b9d6bcd-bbfd-4b2d-9b5d-ab8dfbbd4bed`

## Level 5

***Nr. 21***

Der Benutzer gibt die Anzahl der Zeilen für die folgende Grafik ein:
```
  *
 ***
*****
 ***
  *
```

***Nr. 22***

Erstelle eine Liste wie in Nr. 12. Finde den größten Interval, in welchem die Zahlen unter 30 sind. Beispiel: `44, 32, 29, 22, 32, 29, 20, 11, 26, 26, 65 => 5`

***Nr. 23***

Lass den Benutzer eine Liste von Zahlen eingeben, getrennt von einem Komma. Erstelle eine Liste, die alle Zahlen beinhaltet.