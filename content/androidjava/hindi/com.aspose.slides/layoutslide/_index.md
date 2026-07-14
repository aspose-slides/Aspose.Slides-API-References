---
title: LayoutSlide
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: लेआउट स्लाइड का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/layoutslide/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

लेआउट स्लाइड का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | लेआउट स्लाइड का HeaderFooter प्रबंधक लौटाता है। |
| [getPlaceholderManager()](#getPlaceholderManager--) | लेआउट स्लाइड का प्लेसहोल्डर प्रबंधक लौटाता है। |
| [getMasterSlide()](#getMasterSlide--) | एक लेआउट के लिए मास्टर स्लाइड को लौटाता है या सेट करता है। |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | एक लेआउट के लिए मास्टर स्लाइड को लौटाता है या सेट करता है। |
| [remove()](#remove--) | प्रेजेंटेशन से लेआउट हटाता है। |
| [getThemeManager()](#getThemeManager--) | ओवरराइडिंग थीम प्रबंधक लौटाता है। |
| [getLayoutType()](#getLayoutType--) | इस लेआउट स्लाइड का लेआउट प्रकार लौटाता है। |
| [getDependingSlides()](#getDependingSlides--) | एक एरे लौटाता है जिसमें सभी स्लाइड्स शामिल हैं, जो इस लेआउट स्लाइड पर निर्भर हैं। |
| [hasDependingSlides()](#hasDependingSlides--) | यदि कम से कम एक स्लाइड इस लेआउट स्लाइड पर निर्भर है तो true लौटाता है। |
| [getShowMasterShapes()](#getShowMasterShapes--) | निर्देशित करता है कि मास्टर स्लाइड पर मौजूद आकार स्लाइड्स पर दिखाए जाएँ या नहीं। |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | निर्देशित करता है कि मास्टर स्लाइड पर मौजूद आकार स्लाइड्स पर दिखाए जाएँ या नहीं। |
| [getDrawingGuides()](#getDrawingGuides--) | लेआउट स्लाइड के लिए ड्रॉइंग गाइड्स का संग्रह लौटाता है। |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

लेआउट स्लाइड का HeaderFooter प्रबंधक लौटाता है। केवल-पढ़ने-योग्य [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**वापसी:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```

लेआउट स्लाइड का प्लेसहोल्डर प्रबंधक लौटाता है। केवल-पढ़ने-योग्य [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**वापसी:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```

एक लेआउट के लिए मास्टर स्लाइड को लौटाता है या सेट करता है। पढ़ने/लिखने-योग्य [IMasterSlide](../../com.aspose.slides/imasterslide).

**वापसी:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```

एक लेआउट के लिए मास्टर स्लाइड को लौटाता है या सेट करता है। पढ़ने/लिखने-योग्य [IMasterSlide](../../com.aspose.slides/imasterslide).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### remove() {#remove--}
```
public final void remove()
```

प्रेजेंटेशन से लेआउट हटाता है।

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

ओवरराइडिंग थीम प्रबंधक लौटाता है। केवल-पढ़ने-योग्य [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**वापसी:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```

इस लेआउट स्लाइड का लेआउट प्रकार लौटाता है। केवल-पढ़ने-योग्य [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**वापसी:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

एक एरे लौटाता है जिसमें सभी स्लाइड्स शामिल हैं, जो इस लेआउट स्लाइड पर निर्भर हैं।

**वापसी:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

यदि कम से कम एक स्लाइड इस लेआउट स्लाइड पर निर्भर है तो true लौटाता है। केवल-पढ़ने-योग्य  boolean .

**वापसी:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

निर्देशित करता है कि मास्टर स्लाइड पर मौजूद आकार स्लाइड्स पर दिखाए जाएँ या नहीं। पढ़ने/लिखने-योग्य  boolean .

**वापसी:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

निर्देशित करता है कि मास्टर स्लाइड पर मौजूद आकार स्लाइड्स पर दिखाए जाएँ या नहीं। पढ़ने/लिखने-योग्य  boolean .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

लेआउट स्लाइड के लिए ड्रॉइंग गाइड्स का संग्रह लौटाता है। केवल-पढ़ने-योग्य [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // स्लाइड केंद्र के बाएँ ओर नई लंबवत ड्रॉइंग गाइड जोड़ना
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)