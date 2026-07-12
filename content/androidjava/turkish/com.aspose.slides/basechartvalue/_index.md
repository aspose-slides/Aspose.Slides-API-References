---
title: BaseChartValue
second_title: Aspose.Slides for Android via Java API Referansı
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

Bir chart değerini temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | AsCell, AsCells, AsLiteralString veya AsLiteralDouble özelliğinin türetilmiş sınıflarda geçerli olup olmadığını belirtir. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | AsCell, AsCells, AsLiteralString veya AsLiteralDouble özelliğinin türetilmiş sınıflarda geçerli olup olmadığını belirtir. |
| [getData()](#getData--) | Veri. |
| [setData(Object value)](#setData-java.lang.Object-) | Veri. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

AsCell, AsCells, AsLiteralString veya AsLiteralDouble özelliğinin türetilmiş sınıflarda geçerli olup olmadığını belirtir. Diğer bir deyişle, Data özelliğinin değer tipini belirtir. Okuma/yazma [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

ChartDataPointCollection içindeki noktalar için bu özellik sadece okunur. Bu durumda, bu özelliğin değerini değiştirmek için ChartDataPointCollection.DataSourceTypeFor<...> özelliklerinden birini kullanabilirsiniz.

**Döndürür:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

AsCell, AsCells, AsLiteralString veya AsLiteralDouble özelliğinin türetilmiş sınıflarda geçerli olup olmadığını belirtir. Diğer bir deyişle, Data özelliğinin değer tipini belirtir. Okuma/yazma [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

ChartDataPointCollection içindeki noktalar için bu özellik sadece okunur. Bu durumda, bu özelliğin değerini değiştirmek için ChartDataPointCollection.DataSourceTypeFor<...> özelliklerinden birini kullanabilirsiniz.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getData() {#getData--}
```
public abstract Object getData()
```

Veri. Okuma/yazma Object.

**Döndürür:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Veri. Okuma/yazma Object.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Sadece-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject