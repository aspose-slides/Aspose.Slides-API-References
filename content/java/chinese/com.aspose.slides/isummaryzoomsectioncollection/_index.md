---
title: ISummaryZoomSectionCollection
second_title: Aspose.Slides Java API 参考
description: 表示 Summary Zoom Section 对象的集合。
type: docs
url: /zh/com.aspose.slides/isummaryzoomsectioncollection/
---
**所有实现的接口:**  
com.aspose.slides.IGenericCollection
```
public interface ISummaryZoomSectionCollection extends IGenericCollection<ISummaryZoomSection>
```

表示 Summary Zoom Section 对象的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | 创建新的 Summary Zoom Section 对象并将其添加到集合中 |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | 返回给定章节的 Summary Zoom Section 元素。 |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | 从集合中移除 Summary Zoom Section 对象。 |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | 返回指定 SummaryZoomSection 对象的索引。 |
| [clear()](#clear--) | 从集合中移除所有 SummaryZoomSection 对象。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISummaryZoomSection get_Item(int index)
```

获取指定索引处的元素。只读 [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)

### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection addSummaryZoomSection(ISection section)
```

创建新的 Summary Zoom Section 对象并将其添加到集合中

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 用于新 Summary Zoom Section 元素的章节 [ISection](../../com.aspose.slides/isection) |

如果该章节的元素已存在于集合中，则返回现有元素。

**返回:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - 已添加 [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) 元素

### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection getSummarySection(ISection section)
```

返回给定章节的 Summary Zoom Section 元素。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要查找的章节 [ISection](../../com.aspose.slides/isection) |

**返回:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) 或 null 如果集合不包含该章节的元素。

### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract void removeSummaryZoomSection(ISection section)
```

从集合中移除 Summary Zoom Section 对象。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 要移除其 Summary Zoom Section 元素的章节 [ISection](../../com.aspose.slides/isection) |

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public abstract int indexOf(ISummaryZoomSection summaryZoomSection)
```

返回指定 SummaryZoomSection 对象的索引。

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
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | 要查找的 SummaryZoomSection 对象 [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) |

**返回:**
int - SummaryZoomSection 对象的索引，若对象不属于此集合则返回 -1

### clear() {#clear--}
```
public abstract void clear()
```

从集合中移除所有 SummaryZoomSection 对象。

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
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