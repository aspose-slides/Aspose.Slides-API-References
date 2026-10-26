---
title: SummaryZoomSection
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示 Summary Zoom 框架中的 Summary Zoom Section 对象。
type: docs
url: /zh/com.aspose.slides/summaryzoomsection/
---
**继承:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject), [com.aspose.slides.SectionZoomFrame](../../com.aspose.slides/sectionzoomframe)

**所有实现的接口:**
[com.aspose.slides.ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
```
public class SummaryZoomSection extends SectionZoomFrame implements ISummaryZoomSection
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
public final String getTitle()
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
public final void setTitle(String value)
```

Returns the text title of the Summary Zoom Section object.

--------------------

> ```
> Example:
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
public final String getDescription()
```

Returns the text description of the Summary Zoom Section object.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**Returns:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)

Returns the text description of the Summary Zoom Section object.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |