---
title: ZoomFrame
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示投影片中的 Slide Zoom 物件。
type: docs
url: /zh-hant/com.aspose.slides/zoomframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**All Implemented Interfaces:**
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

表示投影片中的 Slide Zoom 物件。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | 取得或設定 Slide Zoom 物件所連結的投影片物件。 |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | 取得或設定 Slide Zoom 物件所連結的投影片物件。 |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

取得或設定 Slide Zoom 物件所連結的投影片物件。讀/寫 [ISlide](../../com.aspose.slides/islide)。

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**返回：**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public final void setTargetSlide(ISlide value)
```

取得或設定 Slide Zoom 物件所連結的投影片物件。讀/寫 [ISlide](../../com.aspose.slides/islide)。

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |