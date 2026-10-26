---
title: IDoubleChartValue
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een double-waarde voor die in een pptx-presentatiedocument op twee manieren kan worden opgeslagen: 1) in cel/cellen van de werkmap die bij een diagram hoort; 2) als letterlijke waarde.
type: docs
url: /nl/com.aspose.slides/idoublechartvalue/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

Stelt een double-waarde voor die in een pptx-presentatiedocument op twee manieren kan worden opgeslagen: 1) in cel/cellen van de werkmap die bij een diagram hoort; 2) als letterlijke waarde.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Retourneert of stelt de letterlijke double-waarde in als DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Retourneert of stelt de letterlijke double-waarde in als DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Converteert naar double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


Retourneert of stelt de letterlijke double-waarde in als DataSourceType = Charts.DataSourceType.DoubleLiterals. Lezen/schrijven double.

**Retour:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


Retourneert of stelt de letterlijke double-waarde in als DataSourceType = Charts.DataSourceType.DoubleLiterals. Lezen/schrijven double.

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
double - Double waarde.