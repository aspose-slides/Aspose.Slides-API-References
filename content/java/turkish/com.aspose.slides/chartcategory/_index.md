---
title: ChartCategory
second_title: Aspose.Slides for Java API Referansı
description: Grafik kategorilerini temsil eder.
type: docs
url: /tr/com.aspose.slides/chartcategory/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

Grafik kategorilerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getUseCell()](#getUseCell--) | true ise AsCell özelliği geçerlidir. |
| [getAsCell()](#getAsCell--) | IChartDataCell nesnesini döndürür veya ayarlar. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | IChartDataCell nesnesini döndürür veya ayarlar. |
| [getAsLiteral()](#getAsLiteral--) | AsLiteral nesnesini döndürür veya ayarlar. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | AsLiteral nesnesini döndürür veya ayarlar. |
| [getValue()](#getValue--) | UseCell true ise bu özellik AsCell.Value özelliğini temsil eder. |
| [setValue(Object value)](#setValue-java.lang.Object-) | UseCell true ise bu özellik AsCell.Value özelliğini temsil eder. |
| [getGroupingLevels()](#getGroupingLevels--) | Grafik kategori gruplama seviyelerinin değerlerinin yönetilen konteyneri. |
| [getCachedValue()](#getCachedValue--) | Bir grafik kategorisinin önbelleğe alınmış değerini alır. |
| [remove()](#remove--) | Kategoriyi grafikten kaldırır. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

Eğer true ise AsCell özelliği geçerlidir. Başka bir deyişle, çalışma sayfası kategori depolamak için kullanılır (bu durumda çok seviyeli kategori desteklenir). Eğer false ise AsLiteral özelliği geçerlidir. Başka bir deyişle, çalışma sayfası KATEGORİ depolamak için kullanılmaz (ve bu durumda çok seviyeli kategori desteklenmez). Salt-okunur boolean.

For change value of this property (for all categories in collection) set new value to ChartCategoryCollection.UseCells property.

**Döndürür:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

IChartDataCell nesnesini döndürür veya ayarlar. Kategori çok seviyeli ise seviye "0" için IChartDataCell nesnesi kullanılır. Okunabilir/Yazılabilir [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

IChartDataCell nesnesini döndürür veya ayarlar. Kategori çok seviyeli ise seviye "0" için IChartDataCell nesnesi kullanılır. Okunabilir/Yazılabilir [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

AsLiteral nesnesini döndürür veya ayarlar. Okunabilir/Yazılabilir Object.

**Döndürür:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

AsLiteral nesnesini döndürür veya ayarlar. Okunabilir/Yazılabilir Object.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

UseCell true ise bu özellik AsCell.Value özelliğini temsil eder. UseCell false ise bu özellik AsLiteral özelliğini temsil eder. Okunabilir/Yazılabilir Object.

**Döndürür:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

UseCell true ise bu özellik AsCell.Value özelliğini temsil eder. UseCell false ise bu özellik AsLiteral özelliğini temsil eder. Okunabilir/Yazılabilir Object.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

Grafik kategori gruplama seviyelerinin değerlerinin yönetilen konteyneri. Çok seviyeli kategori birden fazla gruplama seviyesi içerir. Gruplama seviyelerinin indekslemesi sıfır tabanlıdır. Salt-okunur [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Döndürür:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

Bir grafik kategorisinin önbelleğe alınmış değerini alır. Salt-okunur [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx")
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // Tüm önbelleğe alınmış grafik kategori değerlerini yazdır.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      pres.dispose();
>  }
> ```


**Döndürür:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### remove() {#remove--}
```
public final void remove()
```

Kategoriyi grafikten kaldırır.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject