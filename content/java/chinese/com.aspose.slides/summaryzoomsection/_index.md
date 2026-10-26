---
title: SummaryZoomSection
second_title: Aspose.Slides for Java API 参考
description: 表示 Summary Zoom 框架中的 Summary Zoom Section 对象。
type: docs
url: /zh/com.aspose.slides/summaryzoomsection/
---
**继承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject), [com.aspose.slides.SectionZoomFrame](../../com.aspose.slides/sectionzoomframe)

**所有实现的接口：**
[com.aspose.slides.ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
```
public class SummaryZoomSection extends SectionZoomFrame implements ISummaryZoomSection
```

表示 Summary Zoom frame 中的 Summary Zoom Section 对象。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTitle()](#getTitle--) | 返回 Summary Zoom Section object 的文本标题。 |
| [setTitle(String value)](#setTitle-java.lang.String-) | 返回 Summary Zoom Section object 的文本标题。 |
| [getDescription()](#getDescription--) | 返回 Summary Zoom Section object 的文本描述。 |
| [setDescription(String value)](#setDescription-java.lang.String-) | 返回 Summary Zoom Section object 的文本描述。 |
### getTitle() {#getTitle--}
```
public final String getTitle()
```


返回 Summary Zoom Section object 的文本标题。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```


**返回：**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


返回 Summary Zoom Section object 的文本标题。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


返回 Summary Zoom Section object 的文本描述。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**返回：**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


返回 Summary Zoom Section object 的文本描述。

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |