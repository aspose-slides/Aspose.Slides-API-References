---
title: BaseChartValue
second_title: Aspose.Slides pro Java – referenční dokumentace API
description: Reprezentuje hodnotu grafu.
type: docs
url: /cs/com.aspose.slides/basechartvalue/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Reprezentuje hodnotu grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Určuje, zda je vlastnost AsCell, AsCells, AsLiteralString nebo AsLiteralDouble v potomcích aktuální. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Určuje, zda je vlastnost AsCell, AsCells, AsLiteralString nebo AsLiteralDouble v potomcích aktuální. |
| [getData()](#getData--) | Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Data. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Určuje, zda je vlastnost AsCell, AsCells, AsLiteralString nebo AsLiteralDouble v potomcích aktuální. Jinak řečeno určuje typ hodnoty vlastnosti Data. Čtení/zápis [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Pro body v ChartDataPointCollection je tato vlastnost pouze ke čtení. V tomto případě pro změnu hodnoty této vlastnosti můžete použít jednu z vlastností ChartDataPointCollection.DataSourceTypeFor<...>.

**Vrací:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

Určuje, zda je vlastnost AsCell, AsCells, AsLiteralString nebo AsLiteralDouble v potomcích aktuální. Jinak řečeno určuje typ hodnoty vlastnosti Data. Čtení/zápis [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Pro body v ChartDataPointCollection je tato vlastnost pouze ke čtení. V tomto případě pro změnu hodnoty této vlastnosti můžete použít jednu z vlastností ChartDataPointCollection.DataSourceTypeFor<...>.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

Data. Čtení/zápis Object.

**Vrací:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Data. Čtení/zápis Object.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze ke čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject