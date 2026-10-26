---
title: SectionCollection
second_title: Aspose.Slides for Android via Java API 參考文件
description: 表示一個分節的集合。
type: docs
url: /zh-hant/com.aspose.slides/sectioncollection/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面：**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

表示一個分節的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | 新增從特定投影片開始的投影片分節。 |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | 在集合末端新增空的分節。 |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | 在集合的指定位置新增空的分節。 |
| [size()](#size--) | 取得集合實際包含的元素數量。 |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | 傳回集合中指定分節的索引。 |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | 移除分節以及該分節中包含的投影片。 |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | 移除分節。 |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | 將分節及其投影片從集合移動到指定位置。 |
| [clear()](#clear--) | 從集合中移除所有分節。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將整個集合複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回一個值，指示對集合的存取是否已同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
| [iterator()](#iterator--) | 傳回用於遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 Java 迭代器。 |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

取得指定索引處的元素。唯讀 [ISection](../../com.aspose.slides/isection).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

新增從特定投影片開始的投影片分節。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 分節的名稱 |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | 分節的第一張投影片 |

**返回值:**
[ISection](../../com.aspose.slides/isection) - 已新增的分節。
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

在集合末端新增空的分節。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 分節的名稱 |

**返回值:**
[ISection](../../com.aspose.slides/isection) - 已新增的分節。
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

在集合的指定位置新增空的分節。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 分節的名稱 |
| index | int | 新分節的索引。 |

**返回值:**
[ISection](../../com.aspose.slides/isection) - 已新增的分節。
### size() {#size--}
```
public final int size()
```

取得集合實際包含的元素數量。唯讀 int。

**返回值:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

傳回集合中指定分節的索引。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要查找的分節。 |

**返回值:**
int - 分節的索引，若不屬於此集合則返回 -1。
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

移除分節以及該分節中包含的投影片。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要從集合中移除的分節。 |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

移除分節。該分節中包含的投影片將合併到前一個分節。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要從集合中移除的分節。 |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

將分節及其投影片從集合移動到指定位置。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要移動的分節。 |
| index | int | 目標索引。 |

### clear() {#clear--}
```
public final void clear()
```

從集合中移除所有分節。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將整個集合複製到指定的陣列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列 |
| index | int | 目標陣列中的索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回一個值，指示對集合的存取是否已同步（執行緒安全）。唯讀 boolean。

**返回值:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。

**返回值:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

傳回用於遍歷集合的列舉器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

傳回整個集合的 Java 迭代器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - 整個集合的 java.util.Iterator。