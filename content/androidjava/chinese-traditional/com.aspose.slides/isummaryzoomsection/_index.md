---
title: ISummaryZoomSection
second_title: Aspose.Slides for Android via Java API 參考
description: 代表 Summary Zoom 框架中的 Summary Zoom Section 物件。
type: docs
url: /zh-hant/com.aspose.slides/isummaryzoomsection/
---
**所有已實作的介面：**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
```

代表 Summary Zoom 框架中的 Summary Zoom Section 物件。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getTitle()](#getTitle--) | 傳回 Summary Zoom Section 物件的文字標題。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | 傳回 Summary Zoom Section 物件的文字標題。 |
| [getDescription()](#getDescription--) | 傳回 Summary Zoom Section 物件的文字描述。 |
| [setDescription(String value)](#setDescription-java.lang.String-) | 傳回 Summary Zoom Section 物件的文字描述。 |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```


傳回 Summary Zoom Section 物件的文字標題。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**傳回值：**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
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
public abstract String getDescription()
```


傳回 Summary Zoom Section 物件的文字描述。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**傳回值：**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public abstract void setDescription(String value)
```


傳回 Summary Zoom Section 物件的文字描述。

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