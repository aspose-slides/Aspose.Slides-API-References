---
title: IDrawingGuide
second_title: Aspose.Slides for Java API Reference
description: Represents an adjustable drawing guide.
type: docs
url: /de/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

Stellt einen einstellbaren Zeichenleitfaden dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getOrientation()](#getOrientation--) | Gibt die Orientierung des Zeichenleitfadens zurück oder legt sie fest. |
| [setOrientation(byte value)](#setOrientation-byte-) | Gibt die Orientierung des Zeichenleitfadens zurück oder legt sie fest. |
| [getPosition()](#getPosition--) | Gibt die Position des Zeichenleitfadens in Punkten von der oberen linken Ecke der Folie zurück oder legt sie fest. |
| [setPosition(float value)](#setPosition-float-) | Gibt die Position des Zeichenleitfadens in Punkten von der oberen linken Ecke der Folie zurück oder legt sie fest. |
| [getColor()](#getColor--) | Gibt die Farbe des Zeichenleitfadens zurück oder legt sie fest. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Gibt die Farbe des Zeichenleitfadens zurück oder legt sie fest. |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```


Gibt die Orientierung des Zeichenleitfadens zurück oder legt sie fest. Lesen/Schreiben [Orientation](../../com.aspose.slides/orientation).

**Rückgabe:**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```


Gibt die Orientierung des Zeichenleitfadens zurück oder legt sie fest. Lesen/Schreiben [Orientation](../../com.aspose.slides/orientation).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


Gibt die Position des Zeichenleitfadens in Punkten von der oberen linken Ecke der Folie zurück oder legt sie fest. Lesen/Schreiben float.

--------------------

Der typische Wertebereich ist von null bis zur Folienhöhe für einen horizontalen Leitfaden und von null bis zur Folienbreite für einen vertikalen Leitfaden.

**Rückgabe:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


Gibt die Position des Zeichenleitfadens in Punkten von der oberen linken Ecke der Folie zurück oder legt sie fest. Lesen/Schreiben float.

--------------------

Der typische Wertebereich ist von null bis zur Folienhöhe für einen horizontalen Leitfaden und von null bis zur Folienbreite für einen vertikalen Leitfaden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```


Gibt die Farbe des Zeichenleitfadens zurück oder legt sie fest. Lesen/Schreiben java.awt.Color.

**Rückgabe:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```


Gibt die Farbe des Zeichenleitfadens zurück oder legt sie fest. Lesen/Schreiben java.awt.Color.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.awt.Color |  |