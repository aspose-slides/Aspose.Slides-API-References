---
title: IBaseChartValue
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje hodnotu grafu.
type: docs
url: /cs/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

Reprezentuje hodnotu grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Určuje, zda je vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble aktuální. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Určuje, zda je vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble aktuální. |
| [getData()](#getData--) | Čtení/zápis Object. |
| [setData(Object value)](#setData-java.lang.Object-) | Čtení/zápis Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


Určuje, zda je vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble aktuální. Jinými slovy určuje typ hodnoty vlastnosti Data. Tato vlastnost je jen pro čtení. Pro změnu hodnoty této vlastnosti můžete použít některou z vlastností ChartDataPointCollection.DataSourceTypeFor<...>. Čtení/zápis [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Vrací:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```


Určuje, zda je vlastnost AsCell nebo AsLiteralString nebo AsLiteralDouble aktuální. Jinými slovy určuje typ hodnoty vlastnosti Data. Tato vlastnost je jen pro čtení. Pro změnu hodnoty této vlastnosti můžete použít některou z vlastností ChartDataPointCollection.DataSourceTypeFor<...>. Čtení/zápis [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```


Čtení/zápis Object.

**Vrací:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


Čtení/zápis Object.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object |  |