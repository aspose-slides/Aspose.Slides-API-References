---
title: SizeF
second_title: Aspose.Slides für Android über die Java API Referenz
description: Klasse zur Beschreibung von Breiten- und Höhenmaßen in einer beliebigen Einheit mit Fließkommawerten.
type: docs
url: /de/com.aspose.slides.android/sizef/
---
**Vererbung:**
java.lang.Object
```
public class SizeF
```

Klasse zur Beschreibung von Breiten- und Höhenmaßen in einer beliebigen Einheit mit Fließkommawerten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | Erstelle eine neue SizeF-Instanz. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWidth()](#getWidth--) | Gibt die Breite der Größe zurück. |
| [getHeight()](#getHeight--) | Gibt die Höhe der Größe zurück. |
| [equals(Object obj)](#equals-java.lang.Object-) | Überprüft, ob diese Größe einer anderen Größe entspricht. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Gibt die Größe als Zeichenkette im Format  "WxH"  zurück |
### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Erstelle eine neue SizeF-Instanz.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | float | Die Breite der Größe |
| height | float | Die Höhe der Größe |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Gibt die Breite der Größe zurück.

**Rückgabe:**
float - Breite
### getHeight() {#getHeight--}
```
public float getHeight()
```


Gibt die Höhe der Größe zurück.

**Rückgabe:**
float - Höhe
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Überprüft, ob diese Größe einer anderen Größe entspricht.

Zwei Größen sind genau dann gleich, wenn sowohl ihre Breiten als auch ihre Höhen identisch sind.

Zu diesem Zweck werden die Fließkommawerte von Breite/Höhe als gleich betrachtet, wenn die Methode Float\#floatToIntBits(float).floatToIntBits(float) den identischen  int  Wert zurückgibt, wenn sie auf beide angewendet wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Rückgabe:**
boolean -  true  wenn die Objekte gleich waren,  false  sonst
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Rückgabe:**
int
### toString() {#toString--}
```
public String toString()
```


Gibt die Größe als Zeichenkette im Format  "WxH" zurück.

**Rückgabe:**
java.lang.String - Zeichenkettenrepräsentation der Größe