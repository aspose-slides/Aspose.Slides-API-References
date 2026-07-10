---
title: ISummaryZoomSection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示 Summary Zoom 框架中的 Summary Zoom Section 对象。
type: docs
url: /zh/com.aspose.slides/isummaryzoomsection/
---
**所有已实现的接口：**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
```

表示 Summary Zoom 框架中的 Summary Zoom Section 对象。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTitle()](#getTitle--) | 返回 Summary Zoom Section 对象的文本标题。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | 返回 Summary Zoom Section 对象的文本标题。 |
| [getDescription()](#getDescription--) | 返回 Summary Zoom Section 对象的文本描述。 |
| [setDescription(String value)](#setDescription-java.lang.String-) | 返回 Summary Zoom Section 对象的文本描述。 |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

返回 Summary Zoom Section 对象的文本标题。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

返回 Summary Zoom Section 对象的文本标题。

--------------------

> ```
> 示例:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

返回 Summary Zoom Section 对象的文本描述。

--------------------

> ```
> 示例:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
>  ```

**Returns:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public abstract void setDescription(String value)


返回 Summary Zoom Section 对象的文本描述。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
>  ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |