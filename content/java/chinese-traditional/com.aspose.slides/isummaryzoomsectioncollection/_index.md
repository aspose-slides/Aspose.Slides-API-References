---
title: ISummaryZoomSectionCollection
second_title: Aspose.Slides for Java API 參考
description: 代表 Summary Zoom Section 物件的集合。
type: docs
url: /zh-hant/com.aspose.slides/isummaryzoomsectioncollection/
---
**已實作的介面：**
com.aspose.slides.IGenericCollection
```
public interface ISummaryZoomSectionCollection extends IGenericCollection<ISummaryZoomSection>
```

代表 Summary Zoom Section 物件的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | 建立新的 Summary Zoom Section 物件並將其加入集合。 |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | 回傳給定節的 Summary Zoom Section 元素。 |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | 從集合中移除 Summary Zoom Section 物件。 |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | 回傳指定 SummaryZoomSection 物件的索引。 |
| [clear()](#clear--) | 從集合中移除所有 SummaryZoomSection 物件。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISummaryZoomSection get_Item(int index)
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


**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| index | int |  |

**傳回值：**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection addSummaryZoomSection(ISection section)
```

建立新的 Summary Zoom Section 物件並將其加入集合。

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


**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 新 Summary Zoom Section 元素的 Section [ISection](../../com.aspose.slides/isection)

--------------------

如果集合中已存在該節的元素，則返回已存在的元素。 |
**傳回值：**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - 已新增 [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) 元素
### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection getSummarySection(ISection section)
```

回傳給定節的 Summary Zoom Section 元素。

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


**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 欲查找的 Section [ISection](../../com.aspose.slides/isection) |

**傳回值：**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) 或 null，若集合未包含該節的元素。

### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract void removeSummaryZoomSection(ISection section)
```

從集合中移除 Summary Zoom Section 物件。

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


**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 欲移除其 Summary Zoom Section 元素的 Section [ISection](../../com.aspose.slides/isection)。 |

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public abstract int indexOf(ISummaryZoomSection summaryZoomSection)
```

回傳指定 SummaryZoomSection 物件的索引。

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


**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | 欲查找的 SummaryZoomSection 物件 [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)。 |

**傳回值：**
int - SummaryZoomSection 物件的索引，若物件不屬於此集合則返回 -1。

### clear() {#clear--}
```
public abstract void clear()
```

從集合中移除所有 SummaryZoomSection 物件。

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
