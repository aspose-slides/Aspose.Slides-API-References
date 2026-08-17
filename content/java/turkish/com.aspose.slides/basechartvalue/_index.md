---
title: BaseChartValue
second_title: Aspose.Slides for Java API Referansı
description: Bir grafiğin değerini temsil eder.
type: docs
url: /tr/com.aspose.slides/basechartvalue/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Bir grafik değerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Descendant sınıflarda AsCell, AsCells, AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Descendant sınıflarda AsCell, AsCells, AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. |
| [getData()](#getData--) | Veri. |
| [setData(Object value)](#setData-java.lang.Object-) | Veri. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Descendant sınıflarda AsCell, AsCells, AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. Başka bir deyişle, Data özelliğinin değer türünü belirtir. Okunabilir/Yazılabilir [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

ChartDataPointCollection içindeki noktalar için bu özellik yalnızca okunabilir. Bu durumda bu özelliğin değerini değiştirmek için ChartDataPointCollection.DataSourceTypeFor<...> özelliklerinden birini kullanabilirsiniz.

**Döndürür:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

Descendant sınıflarda AsCell, AsCells, AsLiteralString veya AsLiteralDouble özelliğinin geçerli olup olmadığını belirtir. Başka bir deyişle, Data özelliğinin değer türünü belirtir. Okunabilir/Yazılabilir [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

ChartDataPointCollection içindeki noktalar için bu özellik yalnızca okunabilir. Bu durumda bu özelliğin değerini değiştirmek için ChartDataPointCollection.DataSourceTypeFor<...> özelliklerinden birini kullanabilirsiniz.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |
### getData() {#getData--}
```
public abstract Object getData()
```

Veri. Okunabilir/Yazılabilir Object.

**Döndürür:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Veri. Okunabilir/Yazılabilir Object.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | java.lang.Object |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okunabilir IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject