---
title: IZoomFrame
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示投影片中的 Slide Zoom 物件。
type: docs
url: /zh-hant/com.aspose.slides/izoomframe/
---
**所有已實作的介面：**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

表示投影片中的 Slide Zoom 物件。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | 取得或設定 Slide Zoom 物件所連結的投影片物件。 |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | 取得或設定 Slide Zoom 物件所連結的投影片物件。 |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


取得或設定 Slide Zoom 物件所連結的投影片物件。讀/寫 [ISlide](../../com.aspose.slides/islide)。

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**返回值：**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public abstract void setTargetSlide(ISlide value)
```


取得或設定 Slide Zoom 物件所連結的投影片物件。讀/寫 [ISlide](../../com.aspose.slides/islide)。

--------------------

> ```
> 下一個範例示範更改目標投影片並為 Slide Zoom 物件建立新影像：
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |