---
title: SectionZoomFrame
second_title: Aspose.Slides for Android via Java API 參考文件
description: 表示投影片中的 Section Zoom 物件。
type: docs
url: /zh-hant/com.aspose.slides/sectionzoomframe/
---
**繼承:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**所有實作的介面:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

表示投影片中的 Section Zoom 物件。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | 取得或設定 Section Zoom 物件所鏈結的 section 物件。 |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | 取得或設定 Section Zoom 物件所鏈結的 section 物件。 |
### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```


取得或設定 Section Zoom 物件所鏈結的 section 物件。 讀/寫 [ISection](../../com.aspose.slides/isection).

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

**返回:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)
```


取得或設定 Section Zoom 物件所鏈結的 section 物件。 讀/寫 [ISection](../../com.aspose.slides/isection).

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |