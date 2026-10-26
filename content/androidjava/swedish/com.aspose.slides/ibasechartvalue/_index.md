---
title: IBaseChartValue
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett värde i ett diagram.
type: docs
url: /sv/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

Representerar ett värde i ett diagram.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Anger om AsCell eller AsLiteralString eller AsLiteralDouble egenskap är aktuell. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Anger om AsCell eller AsLiteralString eller AsLiteralDouble egenskap är aktuell. |
| [getData()](#getData--) | Läs/skriv Object. |
| [setData(Object value)](#setData-java.lang.Object-) | Läs/skriv Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


Anger om AsCell eller AsLiteralString eller AsLiteralDouble egenskap är aktuell. Med andra ord anger den typen av värde för egenskapen Data. Denna egenskap är skrivskyddad. För att ändra värdet på denna egenskap kan du använda en av egenskaperna i ChartDataPointCollection.DataSourceTypeFor<...>. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Returnerar:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```


Anger om AsCell eller AsLiteralString eller AsLiteralDouble egenskap är aktuell. Med andra ord anger den typen av värde för egenskapen Data. Denna egenskap är skrivskyddad. För att ändra värdet på denna egenskap kan du använda en av egenskaperna i ChartDataPointCollection.DataSourceTypeFor<...>. Läs/skriv [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```


Läs/skriv Object.

**Returnerar:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


Läs/skriv Object.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Object |  |