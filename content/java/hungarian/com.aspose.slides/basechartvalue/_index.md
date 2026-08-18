---
title: BaseChartValue
second_title: Aspose.Slides Java API Referencia
description: Egy diagram értékét képviseli.
type: docs
url: /hu/com.aspose.slides/basechartvalue/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Egy diagram értékét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Meghatározza, hogy az AsCell, AsCells, AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az leszármazottakban. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Meghatározza, hogy az AsCell, AsCells, AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az leszármazottakban. |
| [getData()](#getData--) | Adat. |
| [setData(Object value)](#setData-java.lang.Object-) | Adat. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```


Meghatározza, hogy az AsCell, AsCells, AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az leszármazottakban. Más szóval meghatározza a Data tulajdonság értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

A ChartDataPointCollection pontjai esetén ez a tulajdonság csak olvasható. Ebben az esetben a tulajdonság értékének módosításához használhatja a ChartDataPointCollection.DataSourceTypeFor<...> tulajdonságok egyikét.

**Visszatérési érték:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```


Meghatározza, hogy az AsCell, AsCells, AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az leszármazottakban. Más szóval meghatározza a Data tulajdonság értékének típusát. Olvasás/írás [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

A ChartDataPointCollection pontjai esetén ez a tulajdonság csak olvasható. Ebben az esetben a tulajdonság értékének módosításához használhatja a ChartDataPointCollection.DataSourceTypeFor<...> tulajdonságok egyikét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```


Adat. Olvasás/írás Object.

**Visszatérési érték:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


Adat. Olvasás/írás Object.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Visszatéríti a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject