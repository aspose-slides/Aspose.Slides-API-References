---
title: ZoomFrame
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
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

| विधि | विवरण |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | स्लाइड ऑब्जेक्ट प्राप्त या सेट करता है जिससे Slide Zoom ऑब्जेक्ट लिंक किया गया है। |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | स्लाइड ऑब्जेक्ट प्राप्त या सेट करता है जिससे Slide Zoom ऑब्जेक्ट लिंक किया गया है। |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

स्लाइड ऑब्जेक्ट प्राप्त या सेट करता है जिससे Slide Zoom ऑब्जेक्ट लिंक किया गया है। पढ़ें/लिखें [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> अगला उदाहरण लक्ष्य स्लाइड को बदलने और Slide Zoom ऑब्जेक्ट के लिए नई छवि बनाने का प्रदर्शन करता है:
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

स्लाइड ऑब्जेक्ट प्राप्त या सेट करता है जिससे Slide Zoom ऑब्जेक्ट लिंक किया गया है। पढ़ें/लिखें [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> अगला उदाहरण लक्ष्य स्लाइड को बदलने और Slide Zoom ऑब्जेक्ट के लिए नई छवि बनाने का प्रदर्शन करता है:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |