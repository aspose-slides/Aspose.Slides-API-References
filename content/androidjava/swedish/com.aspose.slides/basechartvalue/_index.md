---
title: BaseChartValue
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett värde av ett diagram.
type: docs
url: /sv/com.aspose.slides/basechartvalue/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Representerar ett värde av ett diagram.
## Metoder

| Method | Description |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Anger om egenskapen AsCell, AsCells, AsLiteralString eller AsLiteralDouble är aktuell i avledda klasser. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Anger om egenskapen AsCell, AsCells, AsLiteralString eller AsLiteralDouble är aktuell i avledda klasser. |
| [getData()](#getData--) | Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Data. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Anger om egenskapen AsCell, AsCells, AsLiteralString eller AsLiteralDouble är aktuell i avledda klasser. Med andra ord specificerar den typen av värde för Data-egenskapen. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

För punkter i ChartDataPointCollection är denna egenskap skrivskyddad. I detta fall kan du för att ändra värdet på egenskapen använda någon av ChartDataPointCollection.DataSourceTypeFor<...>-egenskaperna.

**Returnerar:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

Anger om egenskapen AsCell, AsCells, AsLiteralString eller AsLiteralDouble är aktuell i avledda klasser. Med andra ord specificerar den typen av värde för Data-egenskapen. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

För punkter i ChartDataPointCollection är denna egenskap skrivskyddad. I detta fall kan du för att ändra värdet på egenskapen använda någon av ChartDataPointCollection.DataSourceTypeFor<...>-egenskaperna.

**Parametrar:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objekt. Endast läsning IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject