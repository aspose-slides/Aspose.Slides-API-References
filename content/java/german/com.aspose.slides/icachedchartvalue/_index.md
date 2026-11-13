---
title: ICachedChartValue
second_title: Aspose.Slides for Java API Reference
description: Stellt einen zwischengespeicherten Diagrammwert dar, z.B. X, Y, Bubble-Größe oder den Hauptwert.
type: docs
url: /de/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

Stellt einen zwischengespeicherten Diagrammwert dar (z.B. X, Y, Bubble-Größe oder den Hauptwert).
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getData()](#getData--) | Liefert das zwischengespeicherte Datenobjekt. |
| [toDouble()](#toDouble--) | Konvertiert den zwischengespeicherten Wert in einen double. |
### getData() {#getData--}
```
public abstract Object getData()
```

Liefert das zwischengespeicherte Datenobjekt. Nur lesbar  Object .

**Rückgabe:**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Konvertiert den zwischengespeicherten Wert in einen double.

**Rückgabe:**
double - Die numerische Darstellung oder Double.NaN, wenn Data (\#getData.getData) null ist oder nicht in einen double konvertiert werden kann.