---
title: ILayoutSlide
second_title: Aspose.Slides Android के लिए Java API संदर्भ के माध्यम से
description: एक लेआउट स्लाइड का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ilayoutslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

एक लेआउट स्लाइड का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | लेआउट स्लाइड का HeaderFooter मैनेजर लौटाता है। |
| [getPlaceholderManager()](#getPlaceholderManager--) | लेआउट स्लाइड का प्लेसहोल्डर मैनेजर लौटाता है। |
| [getMasterSlide()](#getMasterSlide--) | लेआउट के लिए मास्टर स्लाइड को लौटाता या सेट करता है। |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | लेआउट के लिए मास्टर स्लाइड को लौटाता या सेट करता है। |
| [getLayoutType()](#getLayoutType--) | इस लेआउट स्लाइड का लेआउट प्रकार लौटाता है। |
| [hasDependingSlides()](#hasDependingSlides--) | यदि इस लेआउट स्लाइड पर निर्भर कम से कम एक स्लाइड मौजूद है तो true लौटाता है। |
| [getDependingSlides()](#getDependingSlides--) | उस सभी स्लाइडों की ऐरे लौटाता है जो इस लेआउट स्लाइड पर निर्भर हैं। |
| [remove()](#remove--) | प्रेजेंटेशन से लेआउट को हटाता है। |
| [getDrawingGuides()](#getDrawingGuides--) | लेआउट स्लाइड के लिए ड्राइङ गाइड्स का संग्रह लौटाता है। |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

लेआउट स्लाइड का HeaderFooter मैनेजर लौटाता है। केवल पढ़ने योग्य [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)।

**वापसी:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

लेआउट स्लाइड का प्लेसहोल्डर मैनेजर लौटाता है। केवल पढ़ने योग्य [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)।

**वापसी:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

लेआउट के लिए मास्टर स्लाइड को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [IMasterSlide](../../com.aspose.slides/imasterslide)।

**वापसी:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

लेआउट के लिए मास्टर स्लाइड को लौटाता या सेट करता है। पढ़ने/लिखने योग्य [IMasterSlide](../../com.aspose.slides/imasterslide)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

इस लेआउट स्लाइड का लेआउट प्रकार लौटाता है। केवल पढ़ने योग्य [SlideLayoutType](../../com.aspose.slides/slidelayouttype)।

**वापसी:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

यदि इस लेआउट स्लाइड पर निर्भर कम से कम एक स्लाइड मौजूद है तो true लौटाता है। केवल पढ़ने योग्य boolean।

**वापसी:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

उस सभी स्लाइडों की ऐरे लौटाता है जो इस लेआउट स्लाइड पर निर्भर हैं।

**वापसी:**
com.aspose.slides.ISlide[] - उस सभी स्लाइडों की ऐरे जो इस लेआउट स्लाइड पर निर्भर हैं
### remove() {#remove--}
```
public abstract void remove()
```

प्रेजेंटेशन से लेआउट को हटाता है।

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

लेआउट स्लाइड के लिए ड्राइङ गाइड्स का संग्रह लौटाता है। केवल पढ़ने योग्य [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // स्लाइड के केंद्र के बाएँ ओर नया वर्टिकल ड्रॉइंग गाइड जोड़ रहा है
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)