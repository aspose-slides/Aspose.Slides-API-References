---
title: IZoomFrame
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bir slaytta Slide Zoom nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/izoomframe/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

Bir slaytta Slide Zoom nesnesini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Slide Zoom nesnesinin bağlandığı slayt nesnesi. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Slide Zoom nesnesinin bağlandığı slayt nesnesi. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


Slide Zoom nesnesinin bağlandığı slayt nesnesi. Okuma/Yazma [ISlide](../../com.aspose.slides/islide).

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
public abstract void setTargetSlide(ISlide value)
```


Slide Zoom nesnesinin bağlandığı slayt nesnesi. Okuma/Yazma [ISlide](../../com.aspose.slides/islide).

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