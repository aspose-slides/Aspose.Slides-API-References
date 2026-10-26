---
title: IDoubleChartValue
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt een double-waarde voor die kan worden opgeslagen in een pptx-presentatiedocument op twee manieren: 1) in cel/cellen van een werkmap die gerelateerd is aan een diagram; 2) als letterlijke waarde.
type: docs
url: /nl/com.aspose.slides/idoublechartvalue/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

Stelt een double-waarde voor die kan worden opgeslagen in een pptx-presentatiedocument op twee manieren: 1) in cel/cellen van een werkmap die gerelateerd is aan een diagram; 2) als letterlijke waarde.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Geeft de letterlijke double-waarde terug of stelt deze in als DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Geeft de letterlijke double-waarde terug of stelt deze in als DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Converteert naar double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Geeft de letterlijke double-waarde terug of stelt deze in als DataSourceType = Charts.DataSourceType.DoubleLiterals. Lezen/schrijven double.

**Retour:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Geeft de letterlijke double-waarde terug of stelt deze in als DataSourceType = Charts.DataSourceType.DoubleLiterals. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Converteert naar double.

**Retour:**
double - Double-waarde.