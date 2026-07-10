---
title: ISummaryZoomSectionCollection
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示 Summary Zoom Section 对象的集合。
type: docs
url: /zh/com.aspose.slides/isummaryzoomsectioncollection/
---
**所有已实现的接口：**  
com.aspose.slides.IGenericCollection  
```
public interface ISummaryZoomSectionCollection extends IGenericCollection<ISummaryZoomSection>
```

表示一个 Summary Zoom Section 对象的集合。  
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | 创建新的 Summary Zoom Section 对象并将其添加到集合中。 |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | 返回给定章节的 Summary Zoom Section 元素。 |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | 从集合中移除 Summary Zoom Section 对象。 |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | 返回指定 SummaryZoomSection 对象的索引。 |
| [clear()](#clear--) | 移除集合中所有 SummaryZoomSection 对象。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISummaryZoomSection get_Item(int index)
```

获取指定索引处的元素。 只读 [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)。

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection addSummaryZoomSection(ISection section)
```

Creates new Summary Zoom Section object and add it to the collection

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Section for a new Summary Zoom Section element [ISection](../../com.aspose.slides/isection)

--------------------

If an element for this section already exists in the collection, the existing element is returned. |

**Returns:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - Added [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) element
### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection getSummarySection(ISection section)
```

Returns Summary Zoom Section element for the given section.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Section to find [ISection](../../com.aspose.slides/isection) |

**Returns:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) or null if collection does not contains element for the section.
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract void removeSummaryZoomSection(ISection section)
```

Remove Summary Zoom Section object from the collection.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Section for which the Summary Zoom Section element is to be removed [ISection](../../com.aspose.slides/isection). |

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public abstract int indexOf(ISummaryZoomSection summaryZoomSection)
```

Returns an index of the specified SummaryZoomSection object.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | SummaryZoomSection object to find [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection). |

**Returns:**
int - Index of a SummaryZoomSection object or -1 if SummaryZoomSection object not from this collection.
### clear() {#clear--}
```
public abstract void clear()
Removes all SummaryZoomSection objects from the collection.

--------------------

> ```
> 示例演示如何通过索引获取 Summary Zoom Section 元素：
>   
>   Presentation pres = new Presentation("pres.pptx");
>   try {
>        ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>        ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>        collection.clear();
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```