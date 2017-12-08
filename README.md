# Informatikprojekt-2-Nele-und-Marit

[22/11/17, 1. Stunde](#1)

[24/11/17, 2. und 3. Stunde](#2)

[1/12/17, 4. und 5. Stunde](#3)

[6/12/17, 6. Stunde](#4)

[8/12/17, 7. und 8. Stunde](#5)


## Erste Stunde <a name="1"></a>

Wir haben uns dazu entschiedenals nächstes Projekt eine Lernaktivität mit StarlogoTNG zu machen.
Zuerst haben wir uns mit dem Spaceland vertraut gemacht, und gelernt, wie wir zwischen verschiedenen Ansichten wechseln können.


## Zweite und dritte Stunde <a name="2"></a> (Doppelstunde)

### Lernaktivität eins:

In der ersten Lernaktivität haben wir zwei verschiedene Agentenarten erstellt: Schildkröten und Elefanten.
Dann haben wir die Schildkröte mit Hilfe des "forever"-Blocks immer im Quadrat laufen lassen:

![Screenshot01](Bilder/Screenshot.sltng.1.png "sltng")

### Lernaktivität zwei:

Zunächst haben wir eine Variable definiert, die eine bestimmte Anzahl von Schildkröten erzeugt. Um die Variable zu benutzen setzten wir sie unter den "setup"-Block. Den Slider fügen wir im Schildkröten Feld hinzu. Damit die Schildkröten sich zufällig im Spaceland bewegen benutzen wir zwei random-Blöcke:

![Screenshot01](Bilder/Screenshot.sltng.2.png "sltng")

Um die Schildkröten miteinander sprechen zu lassen, wenn sie aufeinandertreffen, haben wir einen "collision"-Block benutzt. In diesen haben wir zwei "say"-Blöcke benutzt:

![Screenshot01](Bilder/Screenshot.sltng.3.png "sltng")


## Vierte und fünfte Stunde <a name="3"></a> (Doppelstunde)

### Lernaktivität drei:

#### Aufgabe eins

Zunächst haben Wir einen "create-do"-Block verwendet, um alle Schildkröten Rot zu färben. 
Um drei verschiedene Farben zu erhalten haben wir zusätzlich zwei "if"-Blöcke und Variablen benutzt:

![Screenshot01](Bilder/Screenshot.sltng.4.png "sltng")

![Screenshot01](Bilder/Screenshot.sltng.5.png "sltng")

#### Aufgabe zwei

Wir benutzten einen "collision"-Block, damit die Schildkröten gelb werden, wenn sie sich treffen:

![Screenshot01](Bilder/Screenshot.sltng.6.png "sltng")

#### Aufgabe drei

Die Aufgabe bestand darin, die Schildkröten verschwinden zu lassen, wenn sie sich treffen. Hierzu haben wir einen "if-then"-Block benutzt. Als Bedingung haben wir nun eingesetzt, dass die Schildkröte die gleiche Farbe hat, wie die mit der sie kollidiert. In diesem Fall soll die Schildkröte sterben.

![Screenshot01](Bilder/Screenshot.sltng.7.png "sltng")


## Sechste Stunde <a name="4"></a>

### Lernaktivität vier:

#### Aufgabe eins

Wir benutzen den "clear everyone"-Block, um alle Agenten zu entfernen. Dann entferne wir den Block, der Schildkröten kreiert aus dem "setup"-Block. Nun wird nur noch ein Elefant erstellt.

![Screenshot01](Bilder/Screenshot.sltng.8.png "sltng")

#### Aufgabe zwei

Die zweite Aufgabe bestand darin, einen Actor so zu programmieren, dass er sich mit den Pfeiltasten steuern lässt. Hierzu benutzten wir im "forever"-Bereich mehrere "if-test-then"-Blöcke. Als if-Bedingung setzten wir die jeweiligen Pfeiltasten ein.
In den Block für die rechte Pfeiltaste setzten wir unter "then" den Befehl, sich um 90° nach rechts zu drehen, und dann einen Schritt nach vorne zu gehen.
Für die linke Pfeiltaste setzten wir die selben Blöcke ein, mit einer Drehung nach links anstelle von rechts.
In den "then"-Bereich des "if"-Blockes für die obere Pfeiltaste setzen wir nur den Befehl "forward" ein, kombiniert mit dem Parameter 1.
Für die untere Pfeiltaste programmierten wir, dass der Agent sich rückwärts bewegt.

Aktiviert man nun im Spaceland den "forever"-Block, so lässt der Elefant sich mit den Pfeiltasten steuern. Drückt man die rechte oder linke Pfeiltaste, so dreht er sich in die entsprechende Richtung, um ihn aber beispielsweise nach rechts laufen zu lassen, muss man zunächst einmal die rechte Pfeiltaste und dann die obere drücken. Würde man nur die rechte mehrmals drücken, so würde er objektiv von oben betrachten nicht nach rechts laufen, sondern sich nur immer wieder um 90° nach rechts drehen, und dann einen Schritt nach vorne machen.

![Screenshot01](Bilder/Screenshot.sltng.9.png "sltng")


## Siebte und achte Stunde Stunde <a name="5"></a> (Doppelstunde)

Zunächst haben wir die Benotung unserer ersten Projekte erhalten.
Danach haben wir uns mit der Klasse gemeinsam einen Text der Verfasser von "TheBeautyAndJoyOfComputing" angeguckt.
Anschließen haben wir die vierte Lernaktivitat unseres Projektes fortgeführt.

#### Aufgabe drei

Damit der Agent, in unserem Fall ein Elefant, Blöcke einsammeln kann, mussten wir zunächst welche kreieren.
Hierzu erstellten wir unter "Edit Breeds" eine neue Klasse, den Block.
Nun fügten wir im Setup-Bereich einen "create-Do"-Block für die Agentenklasse "Block" hinzu.
Wir definierten im Bereich des Blockes einen Slider. Damit wir diesen auch benutzten können, mussten wir im Setup-Bereich dem "create-Do"-Block des Blockes noch die Aufforderung hinzufügen, eine Anzahl von Blöcken mit dem Slider zu kreieren.

Damit der Elefant Blöcke einsammeln und etwas sagen kann, benutzten wir einen "collision"-Block. Beim Block fügten wir "die" hinzu, beim Elefanten "say" und "Ohh, ein Block!". 
Nun kann man den Elefanten im Spaceland so steuern, dass er auf Blöcke trifft. Passiert dies, soverschwindet der Block, und der Elefant sagt: "Ohh, ein Block!"








