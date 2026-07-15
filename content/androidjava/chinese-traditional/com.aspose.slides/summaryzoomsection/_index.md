---
title: SummaryZoomSection
second_title: Aspose.Slides for Android via Java API 參考
description: 代表 Summary Zoom 框架中的 Summary Zoom Section 物件。
type: docs
url: /zh-hant/com.aspose.slides/summaryzoomsection/
---
**繼承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject), [com.aspose.slides.SectionZoomFrame](../../com.aspose.slides/sectionzoomframe)

**所有已實作的介面：**
[com.aspose.slides.ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
```
public class SummaryZoomSection extends SectionZoomFrame implements ISummaryZoomSection
```

代表 Summary Zoom 框架中的 Summary Zoom Section 物件。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getTitle()](#getTitle--) | 傳回 Summary Zoom Section 物件的文字標題。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | 傳回 Summary Zoom Section 物件的文字標題。 |
| [getDescription()](#getDescription--) | 傳回 Summary Zoom Section 物件的文字說明。 |
| [setDescription(String value)](#setDescription-java.lang.String-) | 傳回 Summary Zoom Section 物件的文字說明。 |
### getTitle() {#getTitle--}
```
public final String getTitle()
```


傳回 Summary Zoom Section 物件的文字標題。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```

**回傳值：**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


傳回 Summary Zoom Section 物件的文字標題。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


傳回 Summary Zoom Section 物件的文字說明。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**回傳值：**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


傳回 Summary Zoom Section 物件的文字說明。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |