---
title: IBaseChartValue
second_title: Aspose.Slides for Android via Java API Reference
description: Stelt een waarde van een diagram voor.
type: docs
url: /nl/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

Stelt een waarde van een diagram voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Geeft aan of de AsCell-, AsLiteralString- of AsLiteralDouble-eigenschap actueel is. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Geeft aan of de AsCell-, AsLiteralString- of AsLiteralDouble-eigenschap actueel is. |
| [getData()](#getData--) | Lezen/schrijven Object. |
| [setData(Object value)](#setData-java.lang.Object-) | Lezen/schrijven Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Geeft aan of de AsCell-, AsLiteralString- of AsLiteralDouble-eigenschap actueel is. Met andere woorden specificeert het het type waarde van de Data-eigenschap. Deze eigenschap is alleen-lezen. Voor het wijzigen van de waarde van deze eigenschap kunt u een van de ChartDataPointCollection.DataSourceTypeFor<...>-eigenschappen gebruiken. Lezen/schrijven [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Retourneert:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```

Geeft aan of de AsCell-, AsLiteralString- of AsLiteralDouble-eigenschap actueel is. Met andere woorden specificeert het het type waarde van de Data-eigenschap. Deze eigenschap is alleen-lezen. Voor het wijzigen van de waarde van deze eigenschap kunt u een van de ChartDataPointCollection.DataSourceTypeFor<...>-eigenschappen gebruiken. Lezen/schrijven [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

Lezen/schrijven Object.

**Retourneert:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Lezen/schrijven Object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Object |  |