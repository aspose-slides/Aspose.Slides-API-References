---
title: ZoomFrame
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक स्लाइड में Slide Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/zoomframe/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)  
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

एक स्लाइड में Slide Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।  
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Slide Zoom ऑब्जेक्ट से लिंक किए गए स्लाइड ऑब्जेक्ट को प्राप्त करता है या सेट करता है। |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Slide Zoom ऑब्जेक्ट से लिंक किए गए स्लाइड ऑब्जेक्ट को प्राप्त करता है या सेट करता है। |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Slide Zoom ऑब्जेक्ट से लिंक किए गए स्लाइड ऑब्जेक्ट को प्राप्त करता है या सेट करता है। पढ़ना/लिखना [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**वापसी:**  
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public final void setTargetSlide(ISlide value)
```

Slide Zoom ऑब्जेक्ट से लिंक किए गए स्लाइड ऑब्जेक्ट को प्राप्त करता है या सेट करता है। पढ़ना/लिखना [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**पैरामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |