---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: Represents chart categories.
type: docs
url: /tr/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Grafik kategorilerini temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getUseCell()](#getUseCell--) | Doğruysa AsCell özelliği geçerlidir. |
| [getAsCell()](#getAsCell--) | IChartDataCell nesnesini döndürür veya ayarlar. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | IChartDataCell nesnesini döndürür veya ayarlar. |
| [getAsLiteral()](#getAsLiteral--) | UseCell false olduğunda AsLiteral'i döndürür veya ayarlar. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | UseCell false olduğunda AsLiteral'i döndürür veya ayarlar. |
| [getValue()](#getValue--) | UseCell true olduğunda bu özellik AsCell.Value özelliğini temsil eder. |
| [setValue(Object value)](#setValue-java.lang.Object-) | UseCell true olduğunda bu özellik AsCell.Value özelliğini temsil eder. |
| [getGroupingLevels()](#getGroupingLevels--) | Grafik kategori gruplama seviyelerinin değerlerinin yönetilen konteyneri. |
| [remove()](#remove--) | Kategoriyi grafikten kaldırır. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Doğruysa AsCell özelliği geçerlidir. Başka bir deyişle, çalışma sayfası kategori depolamak için kullanılır (bu durumda çok seviyeli kategori desteklenir). Yanlışsa AsLiteral özelliği geçerlidir. Başka bir deyişle, çalışma sayfası kategori depolamak için KULLANILMAZ (ve bu durumda çok seviyeli kategoriler desteklenmez). Yalnızca okunabilir boolean.

--------------------

Bu özelliğin değerini değiştirmek için (koleksiyondaki tüm kategoriler için) yeni değeri [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) özelliğine ayarlayın.

**Döndürür:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

IChartDataCell nesnesini döndürür veya ayarlar. Kategori çok seviyeli ise seviye "0" için IChartDataCell nesnesi kullanılır. Okunur/yazılır [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Döndürür:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

IChartDataCell nesnesini döndürür veya ayarlar. Kategori çok seviyeli ise seviye "0" için IChartDataCell nesnesi kullanılır. Okunur/yazılır [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

UseCell false olduğunda AsLiteral'i döndürür veya ayarlar. Okunur/yazılır Object.

**Döndürür:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

UseCell false olduğunda AsLiteral'i döndürür veya ayarlar. Okunur/yazılır Object.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

UseCell true olduğunda bu özellik AsCell.Value özelliğini temsil eder. UseCell false olduğunda bu özellik AsLiteral özelliğini temsil eder. Okunur/yazılır Object.

**Döndürür:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

UseCell true olduğunda bu özellik AsCell.Value özelliğini temsil eder. UseCell false olduğunda bu özellik AsLiteral özelliğini temsil eder. Okunur/yazılır Object.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Grafik kategori gruplama seviyelerinin değerlerinin yönetilen konteyneri. Çok seviyeli kategori birden fazla gruplama seviyesi içerir. Grublama seviyeleri sıfır tabanlı indekslenir. Yalnızca okunabilir [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Döndürür:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Kategoriyi grafikten kaldırır.