---
title: ChartCategory
second_title: Aspose.Slides Java API Referansı
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
## Metotlar

| Metod | Açıklama |
| --- | --- |
| [getUseCell()](#getUseCell--) | Eğer doğru ise AsCell özelliği geçerlidir. |
| [getAsCell()](#getAsCell--) | IChartDataCell nesnesini döndürür veya ayarlar. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | IChartDataCell nesnesini döndürür veya ayarlar. |
| [getAsLiteral()](#getAsLiteral--) | AsLiteral nesnesini döndürür veya ayarlar. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | AsLiteral nesnesini döndürür veya ayarlar. |
| [getValue()](#getValue--) | Eğer UseCell doğru ise bu özellik AsCell.Value özelliğini temsil eder. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Eğer UseCell doğru ise bu özellik AsCell.Value özelliğini temsil eder. |
| [getGroupingLevels()](#getGroupingLevels--) | Grafik kategori gruplama seviyelerinin değerlerinin yönetilen konteyneri. |
| [remove()](#remove--) | Kategoriyi grafikten kaldırır. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

Eğer doğru ise AsCell özelliği geçerlidir. Başka bir deyişle, çalışma sayfası kategori depolamak için kullanılır (bu durumda çok seviyeli kategori desteklenir). Eğer yanlış ise AsLiteral özelliği geçerlidir. Başka bir deyişle, çalışma sayfası kategori depolamak için KULLANILMAZ (ve bu durumda çok seviyeli kategoriler desteklenmez). Yalnızca okuma boolean.

For change value of this property (for all categories in collection) set new value to ChartCategoryCollection.UseCells property.

**Döndürür:**  
boolean

### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

IChartDataCell nesnesini döndürür veya ayarlar. Kategori çok seviyeli ise seviye "0" için IChartDataCell nesnesi kullanılır. Okuma/yazma [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Döndürür:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

IChartDataCell nesnesini döndürür veya ayarlar. Kategori çok seviyeli ise seviye "0" için IChartDataCell nesnesi kullanılır. Okuma/yazma [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

AsLiteral nesnesini döndürür veya ayarlar. Okuma/yazma Object.

**Döndürür:**  
java.lang.Object

### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

AsLiteral nesnesini döndürür veya ayarlar. Okuma/yazma Object.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

Eğer UseCell doğru ise bu özellik AsCell.Value özelliğini temsil eder. Eğer UseCell yanlış ise bu özellik AsLiteral özelliğini temsil eder. Okuma/yazma Object.

**Döndürür:**  
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Eğer UseCell doğru ise bu özellik AsCell.Value özelliğini temsil eder. Eğer UseCell yanlış ise bu özellik AsLiteral özelliğini temsil eder. Okuma/yazma Object.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

Grafik kategori gruplama seviyelerinin değerlerinin yönetilen konteyneri. Çok seviyeli kategori birden fazla gruplama seviyesi içerir. Gruplama seviyeleri indekslemesi sıfır tabanlıdır. Yalnızca okuma [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Döndürür:**  
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)

### remove() {#remove--}
```
public final void remove()
```

Kategoriyi grafikten kaldırır.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okuma IDOMObject.

**Döndürür:**  
com.aspose.slides.IDOMObject