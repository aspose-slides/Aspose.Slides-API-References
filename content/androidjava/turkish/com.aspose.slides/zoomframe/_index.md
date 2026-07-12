---
title: ZoomFrame
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir slaytta Slide Zoom nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/zoomframe/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

Bir slaytta Slide Zoom nesnesini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Slide Zoom nesnesinin bağlandığı slayt nesnesini alır veya ayarlar. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Slide Zoom nesnesinin bağlandığı slayt nesnesini alır veya ayarlar. |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Slide Zoom nesnesinin bağlandığı slayt nesnesini alır veya ayarlar. Okunur/Yazılır [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**Döndürür:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public final void setTargetSlide(ISlide value)
```

Slide Zoom nesnesinin bağlandığı slayt nesnesini alır veya ayarlar. Okunur/Yazılır [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |