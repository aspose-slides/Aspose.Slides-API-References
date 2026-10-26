---
title: ISectionZoomFrame
second_title: Aspose.Slides for Java API 参考
description: 表示幻灯片中的 Section Zoom 对象。
type: docs
url: /zh/com.aspose.slides/isectionzoomframe/
---
**所有已实现的接口：**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

表示幻灯片中的 Section Zoom 对象。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | 获取或设置 Section Zoom 对象链接的节对象。 |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | 获取或设置 Section Zoom 对象链接的节对象。 |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```

获取或设置 Section Zoom 对象链接的节对象。读/写 [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> This example demonstrates changing target section and creates a new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```

获取或设置 Section Zoom 对象链接的节对象。读/写 [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> This example demonstrates changing target section and creates a new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |