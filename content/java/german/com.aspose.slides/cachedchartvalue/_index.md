---
title: CachedChartValue
second_title: Aspose.Slides für Java API Referenz
description: Stellt einen zwischengespeicherten Diagrammwert dar, z.B. X, Y, Blasengröße oder den Hauptwert.
type: docs
url: /de/com.aspose.slides/cachedchartvalue/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

Stellt einen zwischengespeicherten Diagrammwert dar (z.B. X, Y, Blasengröße oder den Hauptwert).
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [toString()](#toString--) | Gibt eine Zeichenkettenrepräsentation des zwischengespeicherten Wertes zurück. |
| [toDouble()](#toDouble--) | Konvertiert den zwischengespeicherten Wert zu einem double. |
| [getData()](#getData--) | Ruft das zwischengespeicherte Datenobjekt ab. |
### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```


### toString() {#toString--}
```
public String toString()
```

Gibt eine Zeichenkettenrepräsentation des zwischengespeicherten Wertes zurück.

**Rückgabe:**
java.lang.String
### toDouble() {#toDouble--}
```
public final double toDouble()
```

Konvertiert den zwischengespeicherten Wert zu einem double.

**Rückgabe:**
double - Die numerische Darstellung oder Double.NaN, wenn Data (\#getData.getData/\#setData(Object).setData(Object)) null ist oder nicht in einen double konvertiert werden kann.
### getData() {#getData--}
```
public final Object getData()
```

Ruft das zwischengespeicherte Datenobjekt ab. Schreibgeschützt  Object .

**Rückgabe:**
java.lang.Object