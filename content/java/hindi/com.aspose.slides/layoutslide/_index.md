---
title: LayoutSlide
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक लेआउट स्लाइड का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/layoutslide/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

लेआउट स्लाइड का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | लेआउट स्लाइड का HeaderFooter प्रबंधक लौटाता है। |
| [getPlaceholderManager()](#getPlaceholderManager--) | लेआउट स्लाइड का placeholder प्रबंधक लौटाता है। |
| [getMasterSlide()](#getMasterSlide--) | एक लेआउट के लिए master slide को लौटाता या सेट करता है। |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | एक लेआउट के लिए master slide को लौटाता या सेट करता है। |
| [remove()](#remove--) | प्रस्तुति से लेआउट हटाता है। |
| [getThemeManager()](#getThemeManager--) | ओवरराइडिंग theme प्रबंधक लौटाता है। |
| [getLayoutType()](#getLayoutType--) | इस लेआउट स्लाइड का लेआउट प्रकार लौटाता है। |
| [getDependingSlides()](#getDependingSlides--) | एक ऐरे लौटाता है जिसमें सभी स्लाइड्स होते हैं, जो इस लेआउट स्लाइड पर निर्भर हैं। |
| [hasDependingSlides()](#hasDependingSlides--) | यदि कम से कम एक स्लाइड है जो इस लेआउट स्लाइड पर निर्भर है तो true लौटाता है। |
| [getShowMasterShapes()](#getShowMasterShapes--) | निर्दिष्ट करता है कि master slide की आकृतियाँ स्लाइड्स पर दिखेंगी या नहीं। |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | निर्दिष्ट करता है कि master slide की आकृतियाँ स्लाइड्स पर दिखेंगी या नहीं। |
| [getDrawingGuides()](#getDrawingGuides--) | लेआउट स्लाइड के लिए drawing guides का संग्रह लौटाता है। |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

लेआउट स्लाइड का HeaderFooter प्रबंधक लौटाता है। केवल-पढ़ने योग्य [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**लौटाता है:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```

लेआउट स्लाइड का placeholder प्रबंधक लौटाता है। केवल-पढ़ने योग्य [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**लौटाता है:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```

एक लेआउट के लिए master slide को लौटाता या सेट करता है। पढ़ना/लिखना [IMasterSlide](../../com.aspose.slides/imasterslide)।

**लौटाता है:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```

एक लेआउट के लिए master slide को लौटाता या सेट करता है। पढ़ना/लिखना [IMasterSlide](../../com.aspose.slides/imasterslide)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### remove() {#remove--}
```
public final void remove()
```

प्रस्तुति से लेआउट हटाता है।
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

ओवरराइडिंग theme प्रबंधक लौटाता है। केवल-पढ़ने योग्य [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)।

**लौटाता है:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```

इस लेआउट स्लाइड का लेआउट प्रकार लौटाता है। केवल-पढ़ने योग्य [SlideLayoutType](../../com.aspose.slides/slidelayouttype)।

**लौटाता है:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

एक ऐरे लौटाता है जिसमें सभी स्लाइड्स होते हैं, जो इस लेआउट स्लाइड पर निर्भर हैं।

**लौटाता है:**
com.aspose.slides.ISlide[] - ऐरे [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

यदि कम से कम एक स्लाइड है जो इस लेआउट स्लाइड पर निर्भर है तो true लौटाता है। केवल-पढ़ने योग्य boolean ।

**लौटाता है:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

निर्दिष्ट करता है कि master slide की आकृतियाँ स्लाइड्स पर दिखेंगी या नहीं। पढ़ना/लिखना boolean ।

**लौटाता है:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

निर्दिष्ट करता है कि master slide की आकृतियाँ स्लाइड्स पर दिखेंगी या नहीं। पढ़ना/लिखना boolean .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

लेआउट स्लाइड के लिए drawing guides का संग्रह लौटाता है। केवल-पढ़ने योग्य [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // स्लाइड केंद्र के बाईं ओर नया ऊर्ध्वाधर ड्रॉइंग गाइड जोड़ना
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**लौटाता है:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)