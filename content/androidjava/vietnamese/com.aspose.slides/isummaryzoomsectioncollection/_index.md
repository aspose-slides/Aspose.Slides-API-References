---
title: ISummaryZoomSectionCollection
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Đại diện cho một bộ sưu tập các đối tượng Summary Zoom Section.
type: docs
url: /vi/com.aspose.slides/isummaryzoomsectioncollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ISummaryZoomSectionCollection extends IGenericCollection<ISummaryZoomSection>
```

Represents a collection of Summary Zoom Section objects.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | Tạo đối tượng Summary Zoom Section mới và thêm nó vào bộ sưu tập |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | Trả về phần tử Summary Zoom Section cho phần được cung cấp. |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | Xóa đối tượng Summary Zoom Section khỏi bộ sưu tập. |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | Trả về chỉ mục của đối tượng SummaryZoomSection được chỉ định. |
| [clear()](#clear--) | Xóa tất cả các đối tượng SummaryZoomSection khỏi bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISummaryZoomSection get_Item(int index)
```


Lấy phần tử tại chỉ mục được chỉ định. Chỉ đọc [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

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
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection addSummaryZoomSection(ISection section)
```


Tạo đối tượng Summary Zoom Section mới và thêm nó vào bộ sưu tập

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
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Phần cho một phần tử Summary Zoom Section mới [ISection](../../com.aspose.slides/isection)

--------------------

Nếu một phần tử cho phần này đã tồn tại trong bộ sưu tập, phần tử hiện có sẽ được trả về. |

**Returns:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - Đã thêm [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) phần tử
### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection getSummarySection(ISection section)
```


Trả về phần tử Summary Zoom Section cho phần được cung cấp.

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
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Phần để tìm [ISection](../../com.aspose.slides/isection) |

**Returns:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) hoặc null nếu bộ sưu tập không chứa phần tử cho phần này.
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract void removeSummaryZoomSection(ISection section)
```


Xóa đối tượng Summary Zoom Section khỏi bộ sưu tập.

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
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Phần mà phần tử Summary Zoom Section sẽ bị xóa [ISection](../../com.aspose.slides/isection). |

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public abstract int indexOf(ISummaryZoomSection summaryZoomSection)
```


Trả về chỉ mục của đối tượng SummaryZoomSection được chỉ định.

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
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | Đối tượng SummaryZoomSection để tìm [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection). |

**Returns:**
int - Chỉ mục của một đối tượng SummaryZoomSection hoặc -1 nếu đối tượng SummaryZoomSection không thuộc bộ sưu tập này.
### clear() {#clear--}
```
public abstract void clear()
```


Xóa tất cả các đối tượng SummaryZoomSection khỏi bộ sưu tập.

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