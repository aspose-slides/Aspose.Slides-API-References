---
title: BaseChartValue
second_title: Aspose.Slides dla Androida za pośrednictwem odniesienia API Java
description: Reprezentuje wartość wykresu.
type: docs
url: /pl/com.aspose.slides/basechartvalue/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Reprezentuje wartość wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Określa, czy właściwość AsCell, AsCells, AsLiteralString lub AsLiteralDouble jest aktualna w klasach pochodnych. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Określa, czy właściwość AsCell, AsCells, AsLiteralString lub AsLiteralDouble jest aktualna w klasach pochodnych. |
| [getData()](#getData--) | Dane. |
| [setData(Object value)](#setData-java.lang.Object-) | Dane. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Określa, czy właściwość AsCell, AsCells, AsLiteralString lub AsLiteralDouble jest aktualna w klasach pochodnych. Innymi słowy określa typ wartości właściwości Data. Odczyt/zapis [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Dla punktów w ChartDataPointCollection ta właściwość jest tylko do odczytu. W tym przypadku, aby zmienić wartość tej właściwości, możesz użyć jednej z właściwości ChartDataPointCollection.DataSourceTypeFor<...>.

**Zwraca:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

Określa, czy właściwość AsCell, AsCells, AsLiteralString lub AsLiteralDouble jest aktualna w klasach pochodnych. Innymi słowy określa typ wartości właściwości Data. Odczyt/zapis [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Dla punktów w ChartDataPointCollection ta właściwość jest tylko do odczytu. W tym przypadku, aby zmienić wartość tej właściwości, możesz użyć jednej z właściwości ChartDataPointCollection.DataSourceTypeFor<...>.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

Dane. Odczyt/zapis Object.

**Zwraca:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Dane. Odczyt/zapis Object.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject