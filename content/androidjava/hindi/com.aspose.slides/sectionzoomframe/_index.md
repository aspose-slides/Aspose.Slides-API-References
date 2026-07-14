---
title: SectionZoomFrame
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक स्लाइड में Section Zoom वस्तु का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/sectionzoomframe/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

एक स्लाइड में Section Zoom वस्तु का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Section Zoom वस्तु द्वारा लिंक किए गए सेक्शन वस्तु को प्राप्त करता है या सेट करता है। |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Section Zoom वस्तु द्वारा लिंक किए गए सेक्शन वस्तु को प्राप्त करता है या सेट करता है। |
### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```

Section Zoom वस्तु द्वारा लिंक किए गए सेक्शन वस्तु को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [ISection](../../com.aspose.slides/isection).

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


**वापसी:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)
```

Section Zoom वस्तु द्वारा लिंक किए गए सेक्शन वस्तु को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> अगला उदाहरण लक्ष्य सेक्शन को बदलने और सेक्शन ज़ूम ऑब्जेक्ट के लिए नई छवि बनाने का प्रदर्शन करता है:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |