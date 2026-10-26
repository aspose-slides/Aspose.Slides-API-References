---
title: IChartCategory
second_title: Aspose.Slides for Android via Java API Reference
description: Grafik kategorilerini temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Grafik kategorilerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getUseCell()](#getUseCell--) | If true then AsCell property is actual. |
| [getAsCell()](#getAsCell--) | Returns or sets IChartDataCell object. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returns or sets IChartDataCell object. |
| [getAsLiteral()](#getAsLiteral--) | Returns or sets AsLiteral if UseCell is false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Returns or sets AsLiteral if UseCell is false. |
| [getValue()](#getValue--) | If UseCell is true then this property represents AsCell.Value property. |
| [setValue(Object value)](#setValue-java.lang.Object-) | If UseCell is true then this property represents AsCell.Value property. |
| [getGroupingLevels()](#getGroupingLevels--) | Managed container of the values of the chart category grouping levels. |
| [remove()](#remove--) | Removes category from chart. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```


Doğruysa AsCell özelliği geçerlidir. Diğer bir ifadeyle, çalışma sayfası kategori depolamak için kullanılır (bu durumda çok seviyeli kategori desteklenir). Yanlışsa AsLiteral özelliği geçerlidir. Diğer bir ifadeyle, çalışma sayfası kategori depolamak için kullanılmaz (ve bu durumda çok seviyeli kategoriler desteklenmez). Yalnızca okunabilir boolean.

--------------------

Bu özelliğin değerini değiştirmek için (koleksiyondaki tüm kategoriler için) yeni değeri [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) özelliğine ayarlayın.

### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```


IChartDataCell nesnesini döndürür veya ayarlar. Kategori çok seviyeli ise seviyeye "0" IChartDataCell nesnesi kullanılır. Okunabilir/Yazılabilir [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```


IChartDataCell nesnesini döndürür veya ayarlar. Kategori çok seviyeli ise seviyeye "0" IChartDataCell nesnesi kullanılır. Okunabilir/Yazılabilir [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```


UseCell false olduğunda AsLiteral'ı döndürür veya ayarlar. Okunabilir/Yazılabilir Object.

**Döndürür:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```


UseCell false olduğunda AsLiteral'ı döndürür veya ayarlar. Okunabilir/Yazılabilir Object.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```


UseCell true ise bu özellik AsCell.Value özelliğini temsil eder. UseCell false ise bu özellik AsLiteral özelliğini temsil eder. Okunabilir/Yazılabilir Object.

**Döndürür:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


UseCell true ise bu özellik AsCell.Value özelliğini temsil eder. UseCell false ise bu özellik AsLiteral özelliğini temsil eder. Okunabilir/Yazılabilir Object.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```


Grafik kategori gruplayıcı seviyelerinin değerlerinin yönetilen konteyneri. Çok seviyeli kategori birden fazla gruplayıcı seviye içerir. Gruplayıcı seviyelerin indeksi sıfır tabanlıdır. Yalnızca okunabilir [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Döndürür:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```


Kategoriyi grafikten kaldırır.