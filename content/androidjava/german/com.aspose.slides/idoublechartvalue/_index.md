---
title: IDoubleChartValue
second_title: Aspose.Slides für Android über Java API Referenz
description: Doppelwert darstellen, der in einer pptx-Präsentationsdatei auf zwei Arten gespeichert werden kann: 1) in Zelle/Zellen einer Arbeitsmappe, die einem Diagramm zugeordnet ist; 2) als wörtlicher Wert.
type: docs
url: /de/com.aspose.slides/idoublechartvalue/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

Stellt einen double-Wert dar, der in einer pptx-Präsentationsdatei auf zwei Arten gespeichert werden kann: 1) in Zelle/Zellen einer Arbeitsmappe, die einem Diagramm zugeordnet ist; 2) als wörtlicher Wert.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Gibt den wörtlichen double-Wert zurück oder setzt ihn, wenn DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Gibt den wörtlichen double-Wert zurück oder setzt ihn, wenn DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Konvertiert zu double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Gibt den wörtlichen double-Wert zurück oder setzt ihn, wenn DataSourceType = Charts.DataSourceType.DoubleLiterals. Lese-/Schreibzugriff double.

**Rückgabe:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Gibt den wörtlichen double-Wert zurück oder setzt ihn, wenn DataSourceType = Charts.DataSourceType.DoubleLiterals. Lese-/Schreibzugriff double.

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
double - Double value.