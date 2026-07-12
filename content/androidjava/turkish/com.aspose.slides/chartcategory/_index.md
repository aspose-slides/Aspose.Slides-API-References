---
title: ChartCategory
second_title: Aspose.Slides Android için Java API Referansı
description: Grafik kategorilerini temsil eder.
type: docs
url: /tr/com.aspose.slides/chartcategory/
---
**Miras:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

Grafik kategorilerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getUseCell()](#getUseCell--) | Doğru ise AsCell özelliği geçerli olur. |
| [getAsCell()](#getAsCell--) | IChartDataCell nesnesini döndürür veya ayarlar. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | IChartDataCell nesnesini döndürür veya ayarlar. |
| [getAsLiteral()](#getAsLiteral--) | AsLiteral nesnesini döndürür veya ayarlar. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | AsLiteral nesnesini döndürür veya ayarlar. |
| [getValue()](#getValue--) | UseCell doğru ise bu özellik AsCell.Value özelliğini temsil eder. |
| [setValue(Object value)](#setValue-java.lang.Object-) | UseCell doğru ise bu özellik AsCell.Value özelliğini temsil eder. |
| [getGroupingLevels()](#getGroupingLevels--) | Grafik kategori gruplama seviyelerinin değerlerinin yönetilen kapsayıcısı. |
| [remove()](#remove--) | Kategoriyi grafikten kaldırır. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```


Doğru ise AsCell özelliği geçerlidir. Diğer bir deyişle, çalışma sayfası kategoriyi depolamak için kullanılır (bu durum çok seviyeli bir kategoriyi destekler). Yanlış ise AsLiteral özelliği geçerlidir. Diğer bir deyişle, çalışma sayfası KATEGORİYİ depolamak için kullanılmaz (ve bu durumda çok seviyeli kategorileri desteklemez). Salt okunur boolean.

--------------------

Bu özelliğin değerini değiştirmek için (koleksiyondaki tüm kategoriler için) yeni değeri ChartCategoryCollection.UseCells özelliğine ayarlayın.

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


Grafik kategori gruplama seviyelerinin değerlerinin yönetilen kapsayıcısı. Çok seviyeli kategori birden fazla gruplama seviyesi içerir. Gruplama seviyelerinin indekslemesi sıfır tabanlıdır. Salt okunur [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

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


Parent_Immediate nesnesini döndürür. Salt okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject