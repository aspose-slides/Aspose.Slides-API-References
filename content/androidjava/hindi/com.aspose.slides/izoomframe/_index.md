---
title: IZoomFrame
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक स्लाइड में Slide Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/izoomframe/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

एक स्लाइड में Slide Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।

## विधियां

| विधि | विवरण |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Slide Zoom ऑब्जेक्ट से जुड़ा स्लाइड ऑब्जेक्ट प्राप्त करता है या सेट करता है। |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Slide Zoom ऑब्जेक्ट से जुड़ा स्लाइड ऑब्जेक्ट प्राप्त करता है या सेट करता है। |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Slide Zoom ऑब्जेक्ट से जुड़ा स्लाइड ऑब्जेक्ट प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [ISlide](../../com.aspose.slides/islide)।

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**रिटर्न:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public abstract void setTargetSlide(ISlide value)
```

Slide Zoom ऑब्जेक्ट से जुड़ा स्लाइड ऑब्जेक्ट प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [ISlide](../../com.aspose.slides/islide)।

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |