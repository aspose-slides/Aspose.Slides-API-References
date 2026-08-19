---
title: BaseChartValue
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt een waarde van een diagram.
type: docs
url: /nl/com.aspose.slides/basechartvalue/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Vertegenwoordigt een waarde van een diagram.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Specificeert of de eigenschap AsCell, AsCells, AsLiteralString of AsLiteralDouble geldig is in afstammelingen. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Specificeert of de eigenschap AsCell, AsCells, AsLiteralString of AsLiteralDouble geldig is in afstammelingen. |
| [getData()](#getData--) | Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Data. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```


Specificeert of de eigenschap AsCell, AsCells, AsLiteralString of AsLiteralDouble geldig is in afstammelingen. Met andere woorden specificeert het het type waarde van de eigenschap Data. Lezen/schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Voor punten in ChartDataPointCollection is deze eigenschap alleen-lezen. In dit geval kun je voor het wijzigen van de waarde van deze eigenschap een van de ChartDataPointCollection.DataSourceTypeFor<...> eigenschappen gebruiken.

**Retourneert:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```


Specificeert of de eigenschap AsCell, AsCells, AsLiteralString of AsLiteralDouble geldig is in afstammelingen. Met andere woorden specificeert het het type waarde van de eigenschap Data. Lezen/schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Voor punten in ChartDataPointCollection is deze eigenschap alleen-lezen. In dit geval kun je voor het wijzigen van de waarde van deze eigenschap een van de ChartDataPointCollection.DataSourceTypeFor<...> eigenschappen gebruiken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```


Data. Lezen/schrijven Object.

**Retourneert:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


Data. Lezen/schrijven Object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject