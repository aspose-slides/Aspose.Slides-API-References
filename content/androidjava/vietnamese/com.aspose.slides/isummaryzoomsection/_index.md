---
title: ISummaryZoomSection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một đối tượng Summary Zoom Section trong khung Summary Zoom.
type: docs
url: /vi/com.aspose.slides/isummaryzoomsection/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
```

Biểu diễn một đối tượng Summary Zoom Section trong khung Summary Zoom.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getTitle()](#getTitle--) | Trả về tiêu đề văn bản của đối tượng Summary Zoom Section. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Trả về tiêu đề văn bản của đối tượng Summary Zoom Section. |
| [getDescription()](#getDescription--) | Trả về mô tả văn bản của đối tượng Summary Zoom Section. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Trả về mô tả văn bản của đối tượng Summary Zoom Section. |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```


Trả về tiêu đề văn bản của đối tượng Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**Kết quả trả về:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```


Trả về tiêu đề văn bản của đối tượng Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


Trả về mô tả văn bản của đối tượng Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Kết quả trả về:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public abstract void setDescription(String value)
```


Trả về mô tả văn bản của đối tượng Summary Zoom Section.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |