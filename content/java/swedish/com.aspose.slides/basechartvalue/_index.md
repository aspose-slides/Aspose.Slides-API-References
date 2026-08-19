---
title: BaseChartValue
second_title: Aspose.Slides för Java API-referens
description: Representerar ett värde i ett diagram.
type: docs
url: /sv/com.aspose.slides/basechartvalue/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Representerar ett värde i ett diagram.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Anger om AsCell-, AsCells-, AsLiteralString- eller AsLiteralDouble-egenskapen är aktuell i avledd klasser. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Anger om AsCell-, AsCells-, AsLiteralString- eller AsLiteralDouble-egenskapen är aktuell i avledd klasser. |
| [getData()](#getData--) | Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Data. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```


Anger om AsCell, AsCells, AsLiteralString eller AsLiteralDouble property är aktuell i avledd klasser. Med andra ord anger den typen av värde för Data-egenskapen. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

För punkter i ChartDataPointCollection är denna egenskap skrivskyddad. I detta fall kan du ändra värdet på denna egenskap genom att använda en av ChartDataPointCollection.DataSourceTypeFor<...>-egenskaperna.

**Returnerar:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```


Anger om AsCell, AsCells, AsLiteralString eller AsLiteralDouble property är aktuell i avledd klasser. Med andra ord anger den typen av värde för Data-egenskapen. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

För punkter i ChartDataPointCollection är denna egenskap skrivskyddad. I detta fall kan du ändra värdet på denna egenskap genom att använda en av ChartDataPointCollection.DataSourceTypeFor<...>-egenskaperna.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getData() {#getData--}
```
public abstract Object getData()
```


Data. Läs/skriv Object.

**Returnerar:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


Data. Läs/skriv Object.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Object |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returnerar Parent_Immediate-objektet. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject