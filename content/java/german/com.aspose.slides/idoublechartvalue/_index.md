---
title: IDoubleChartValue
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen double-Wert dar, der in einer pptx-Präsentationsdatei auf zwei Arten gespeichert werden kann: 1) in Zelle/Zellen einer Arbeitsmappe, die dem Diagramm zugeordnet ist, 2) als literal-Wert.
type: docs
url: /de/com.aspose.slides/idoublechartvalue/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

Stellt double-Wert dar, der in einer pptx-Präsentationsdatei auf zwei Arten gespeichert werden kann: 1) in Zelle/Zellen einer Arbeitsmappe, die dem Diagramm zugeordnet ist; 2) als literal Wert.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Gibt den literal-double-Wert zurück oder setzt ihn, wenn DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Gibt den literal-double-Wert zurück oder setzt ihn, wenn DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Konvertiert zu double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


Gibt den literal-double-Wert zurück oder setzt ihn, wenn DataSourceType = Charts.DataSourceType.DoubleLiterals. Lesen/Schreiben double.

**Rückgabe:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


Gibt den literal-double-Wert zurück oder setzt ihn, wenn DataSourceType = Charts.DataSourceType.DoubleLiterals. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Konvertiert zu double.

**Rückgabe:**
double - Double-Wert.