---
title: IBaseChartValue
second_title: Aspose.Slides for Java API Reference
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
| [getDataSourceType()](#getDataSourceType--) | Specificeert of AsCell of AsLiteralString of AsLiteralDouble eigenschap actueel is. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Specificeert of AsCell of AsLiteralString of AsLiteralDouble eigenschap actueel is. |
| [getData()](#getData--) | Lezen/Schrijven Object. |
| [setData(Object value)](#setData-java.lang.Object-) | Lezen/Schrijven Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Specificeert of AsCell of AsLiteralString of AsLiteralDouble eigenschap actueel is. Met andere woorden specificeert het het type van de waarde van de Data-eigenschap. Deze eigenschap is alleen-lezen. Voor het wijzigen van de waarde van deze eigenschap kun je een van de ChartDataPointCollection.DataSourceTypeFor<...>-eigenschappen gebruiken. Lezen/Schrijven [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Retour:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```

Specificeert of AsCell of AsLiteralString of AsLiteralDouble eigenschap actueel is. Met andere woorden specificeert het het type van de waarde van de Data-eigenschap. Deze eigenschap is alleen-lezen. Voor het wijzigen van de waarde van deze eigenschap kun je een van de ChartDataPointCollection.DataSourceTypeFor<...>-eigenschappen gebruiken. Lezen/Schrijven [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

Lezen/Schrijven Object.

**Retour:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Lezen/Schrijven Object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Object |  |