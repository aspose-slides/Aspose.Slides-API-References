---
title: SummaryZoomSectionCollection
second_title: Aspose.Slides Java API 參考
description: 表示 Summary Zoom Section 物件的集合。
type: docs
url: /zh-hant/com.aspose.slides/summaryzoomsectioncollection/
---
**繼承:**  
java.lang.Object, com.aspose.slides.DomObject

**全部已實作的介面:**  
[com.aspose.slides.ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)  
```
public final class SummaryZoomSectionCollection extends DomObject<SummaryZoomFrame> implements ISummaryZoomSectionCollection
```

表示 Summary Zoom Section 物件的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | 建立新的 Summary Zoom Section 物件並將其新增到集合中 |
| [size()](#size--) | 取得集合中實際包含的元素數量。 |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | 傳回指定 SummaryZoomSection 物件的索引。 |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | 從集合中移除 Summary Zoom Section 物件。 |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | 傳回給定 Section 的 Summary Zoom Section 元素。 |
| [clear()](#clear--) | 從集合中移除所有 SummaryZoomSection 物件。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將整個集合複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回指示集合存取是否已同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |

### get_Item(int index) {#get-Item-int-}
```
public final ISummaryZoomSection get_Item(int index)
```

取得指定索引處的元素。唯讀 [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)。

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection zoomSection = collection.get_Item(1);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int |  |

**傳回:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)

### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection addSummaryZoomSection(ISection section)
```

建立新的 Summary Zoom Section 物件並將其新增到集合中

--------------------

> ```
> 此範例示範如何依索引取得 Summary Zoom Section 元素：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection newZoomSection = collection.addSummaryZoomSection(pres.getSections().get_Item(3));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 用於新 Summary Zoom Section 元素的 Section [ISection](../../com.aspose.slides/isection) |

--------------------

如果此 Section 已在集合中存在元素，則回傳該已存在的元素。 |

**傳回:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - 已新增 [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) 元素

### size() {#size--}
```
public final int size()
```

取得集合中實際包含的元素數量。唯讀 int。

**傳回:**
int

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public final int indexOf(ISummaryZoomSection summaryZoomSection)
```

傳回指定 SummaryZoomSection 物件的索引。

--------------------

> ```
> 此範例示範如何依索引取得 Summary Zoom Section 元素：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>       int idx = collection.indexOf(selectedObject);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | 要尋找的 SummaryZoomSection 物件 [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection). |

**傳回:**
int - SummaryZoomSection 物件的索引，若不是此集合中的 SummaryZoomSection 物件則傳回 -1。

### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public final void removeSummaryZoomSection(ISection section)
```

從集合中移除 Summary Zoom Section 物件。

--------------------

> ```
> 此範例示範如何依索引取得 Summary Zoom Section 元素：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.removeSummaryZoomSection(pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要移除其 Summary Zoom Section 元素的 Section [ISection](../../com.aspose.slides/isection). |

### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection getSummarySection(ISection section)
```

傳回給定 Section 的 Summary Zoom Section 元素。

--------------------

> ```
> 此範例示範如何依索引取得 Summary Zoom Section 元素：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要尋找的 Section [ISection](../../com.aspose.slides/isection) |

**傳回:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) 或 null，若集合未包含該 Section 的元素。

### clear() {#clear--}
```
public final void clear()
```

從集合中移除所有 SummaryZoomSection 物件。

--------------------

> ```
> 此範例示範如何依索引取得 Summary Zoom Section 元素：
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.clear();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將整個集合複製到指定的陣列。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列 |
| index | int | 目標陣列中的索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回指示集合存取是否已同步（執行緒安全）的值。唯讀 boolean。

**傳回:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。

**傳回:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iterator()
```

傳回可遍歷集合的列舉器。

**傳回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - 可用於遍歷集合的 IGenericEnumerator

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - 整個集合的 java.util.Iterator