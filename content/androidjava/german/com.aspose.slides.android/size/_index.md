---
title: Size
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Klasse zur Beschreibung von Breiten- und Höhenmaßen in einer beliebigen Einheit.
type: docs
url: /de/com.aspose.slides.android/size/
---
**Vererbung:**
java.lang.Object
```
public class Size
```

Klasse zur Beschreibung von Breiten- und Höhenmaßen in einer beliebigen Einheit.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | Erstellt eine neue Size-Instanz. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWidth()](#getWidth--) | Gibt die Breite der Größe zurück. |
| [getHeight()](#getHeight--) | Gibt die Höhe der Größe zurück. |
| [equals(Object obj)](#equals-java.lang.Object-) | Prüft, ob diese Größe einer anderen Größe entspricht. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Gibt die Größe als Zeichenkette im Format "WxH" zurück. |
### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Erstellt eine neue Size-Instanz.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | int | Die Breite der Größe |
| height | int | Die Höhe der Größe |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Gibt die Breite der Größe zurück.

**Rückgabewert:**
int - width
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gibt die Höhe der Größe zurück.

**Rückgabewert:**
int - height
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Prüft, ob diese Größe einer anderen Größe entspricht.

Zwei Größen sind genau dann gleich, wenn sowohl ihre Breiten als auch ihre Höhen gleich sind.

Ein Größenobjekt ist niemals einem anderen Objekttyp gleich.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Rückgabewert:**
boolean -  true  wenn die Objekte gleich waren,  false  sonst
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Rückgabewert:**
int
### toString() {#toString--}
```
public String toString()
```


Gibt die Größe als Zeichenkette im Format "WxH" zurück.

**Rückgabewert:**
java.lang.String - string representation of the size