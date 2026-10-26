---
title: ISectionZoomFrame
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: स्लाइड में Section Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/isectionzoomframe/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

एक slide में Section Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Section Zoom ऑब्जेक्ट से लिंक किए गए section ऑब्जेक्ट को प्राप्त या सेट करता है। |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Section Zoom ऑब्जेक्ट से लिंक किए गए section ऑब्जेक्ट को प्राप्त या सेट करता है। |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```

Section Zoom ऑब्जेक्ट से लिंक किए गए section ऑब्जेक्ट को प्राप्त या सेट करता है। पढ़ें/लिखें [ISection](../../com.aspose.slides/isection).

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

**वापसी:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```

Section Zoom ऑब्जेक्ट से लिंक किए गए section ऑब्जेक्ट को प्राप्त या सेट करता है। पढ़ें/लिखें [ISection](../../com.aspose.slides/isection).

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |