---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: Grafik kategorilerini temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Grafik kategorilerini temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getUseCell()](#getUseCell--) | Doğru ise AsCell özelliği geçerlidir. |
| [getAsCell()](#getAsCell--) | IChartDataCell nesnesini döndürür veya ayarlar. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | IChartDataCell nesnesini döndürür veya ayarlar. |
| [getAsLiteral()](#getAsLiteral--) | UseCell false ise AsLiteral döndürür veya ayarlar. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | UseCell false ise AsLiteral döndürür veya ayarlar. |
| [getValue()](#getValue--) | UseCell true ise bu özellik AsCell.Value özelliğini temsil eder. |
| [setValue(Object value)](#setValue-java.lang.Object-) | UseCell true ise bu özellik AsCell.Value özelliğini temsil eder. |
| [getCachedValue()](#getCachedValue--) | Bir grafik kategorisinin önbelleğe alınmış değerini alır. |
| [getGroupingLevels()](#getGroupingLevels--) | Grafik kategorisi gruplama seviyelerinin değerlerinin yönetilen konteyneri. |
| [remove()](#remove--) | Kategoriyi grafikten kaldırır. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Doğru ise AsCell özelliği geçerlidir. Başka bir deyişle, çalışma sayfası kategoriyi depolamak için kullanılır (bu durumda çok seviyeli kategori desteklenir). False ise AsLiteral özelliği geçerlidir. Başka bir deyişle, çalışma sayfası KATEGORİYİ depolamak için KULLANILMAZ (ve bu durumda çok seviyeli kategoriler desteklenmez). Salt okunur boolean.

--------------------

Bu özelliğin değerini değiştirmek için (koleksiyondaki tüm kategoriler için) yeni değeri [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) özelliğine ayarlayın.

**Döndürür:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

IChartDataCell nesnesini döndürür veya ayarlar. Kategori çok seviyeli ise "0" seviyesi için IChartDataCell nesnesi kullanılır. Okunur/yazılabilir [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

IChartDataCell nesnesini döndürür veya ayarlar. Kategori çok seviyeli ise "0" seviyesi için IChartDataCell nesnesi kullanılır. Okunur/yazılabilir [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

UseCell false ise AsLiteral döndürür veya ayarlar. Okunur/yazılabilir Object.

**Döndürür:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

UseCell false ise AsLiteral döndürür veya ayarlar. Okunur/yazılabilir Object.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

UseCell true ise bu özellik AsCell.Value özelliğini temsil eder. UseCell false ise bu özellik AsLiteral özelliğini temsil eder. Okunur/yazılabilir Object.

**Döndürür:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

UseCell true ise bu özellik AsCell.Value özelliğini temsil eder. UseCell false ise bu özellik AsLiteral özelliğini temsil eder. Okunur/yazılabilir Object.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object |  |

### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

Bir grafik kategorisinin önbelleğe alınmış değerini alır. Salt okunur [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // Tüm önbelleğe alınmış grafik kategori değerlerini yazdır.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Grafik kategorisi gruplama seviyelerinin değerlerinin yönetilen konteyneri. Çok seviyeli kategori birden fazla gruplama seviyesi içerir. Gruplama seviyeleri indekslemesi sıfır tabanlıdır. Salt okunur [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Döndürür:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Kategoriyi grafikten kaldırır.