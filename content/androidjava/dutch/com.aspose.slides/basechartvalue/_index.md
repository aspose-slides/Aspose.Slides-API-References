---
title: BaseChartValue
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een waarde van een grafiek.
type: docs
url: /nl/com.aspose.slides/basechartvalue/
---
**Overerving:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Vertegenwoordigt een waarde van een grafiek.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Geeft aan of de AsCell-, AsCells-, AsLiteralString- of AsLiteralDouble-eigenschap actueel is in afstammelingen. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Geeft aan of de AsCell-, AsCells-, AsLiteralString- of AsLiteralDouble-eigenschap actueel is in afstammelingen. |
| [getData()](#getData--) | Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Data. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Geeft aan of de AsCell-, AsCells-, AsLiteralString- of AsLiteralDouble-eigenschap actueel is in afstammelingen. Met andere woorden specificeert het het type van de waarde van de Data-eigenschap. Lezen/Schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Voor punten in ChartDataPointCollection is deze eigenschap alleen-lezen. In dit geval kun je voor het wijzigen van de waarde van deze eigenschap een van de ChartDataPointCollection.DataSourceTypeFor<...>-eigenschappen gebruiken.

**Retourneert:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

Geeft aan of de AsCell-, AsCells-, AsLiteralString- of AsLiteralDouble-eigenschap actueel is in afstammelingen. Met andere woorden specificeert het het type van de waarde van de Data-eigenschap. Lezen/Schrijven [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Voor punten in ChartDataPointCollection is deze eigenschap alleen-lezen. In dit geval kun je voor het wijzigen van de waarde van deze eigenschap een van de ChartDataPointCollection.DataSourceTypeFor<...>-eigenschappen gebruiken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getData() {#getData--}
```
public abstract Object getData()
```

Data. Lezen/Schrijven Object.

**Retourneert:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Data. Lezen/Schrijven Object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Object |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate-object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject