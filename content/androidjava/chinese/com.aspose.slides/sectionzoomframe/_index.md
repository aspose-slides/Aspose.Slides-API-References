---
title: SectionZoomFrame
second_title: Aspose.Slides for Android 的 Java API 参考
description: 表示幻灯片中的 Section Zoom 对象。
type: docs
url: /zh/com.aspose.slides/sectionzoomframe/
---
**继承:** java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**所有已实现接口:**  
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)  
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

表示幻灯片中的 Section Zoom 对象。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | 获取或设置 Section Zoom 对象链接到的章节对象。 |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | 获取或设置 Section Zoom 对象链接到的章节对象。 |

### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```

获取或设置 Section Zoom 对象链接到的章节对象。读/写 [ISection](../../com.aspose.slides/isection)。

--------------------

> ```
> Next example demonstrates changing target section and creates new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)

Gets or sets the section object that the Section Zoom object links to. Read/write [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Next example demonstrates changing target section and creates new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |