---
title: ILayoutSlide
second_title: Aspose.Slides for Java API संदर्भ
description: एक लेआउट स्लाइड का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ilayoutslide/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)  
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

एक लेआउट स्लाइड का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | लेआउट स्लाइड का HeaderFooter प्रबंधक लौटाता है। |
| [getPlaceholderManager()](#getPlaceholderManager--) | लेआउट स्लाइड का प्लेसहोल्डर प्रबंधक लौटाता है। |
| [getMasterSlide()](#getMasterSlide--) | लेआउट के लिए मास्टर स्लाइड को लौटाता या सेट करता है। |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | लेआउट के लिए मास्टर स्लाइड को लौटाता या सेट करता है। |
| [getLayoutType()](#getLayoutType--) | इस लेआउट स्लाइड के लेआउट प्रकार को लौटाता है। |
| [hasDependingSlides()](#hasDependingSlides--) | यदि इस लेआउट स्लाइड पर निर्भर कम से कम एक स्लाइड मौजूद हो तो true लौटाता है। |
| [getDependingSlides()](#getDependingSlides--) | एक सरणी लौटाता है जिसमें सभी स्लाइडें शामिल हैं, जो इस लेआउट स्लाइड पर निर्भर हैं। |
| [remove()](#remove--) | प्रेजेंटेशन से लेआउट हटाता है। |
| [getDrawingGuides()](#getDrawingGuides--) | लेआउट स्लाइड के लिए ड्राइंग गाइड्स का संग्रह लौटाता है। |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

लेआउट स्लाइड का HeaderFooter प्रबंधक लौटाता है। केवल पढ़ने योग्य [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)।

**रिटर्न:**  
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)

### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

लेआउट स्लाइड का प्लेसहोल्डर प्रबंधक लौटाता है। केवल पढ़ने योग्य [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)।

**रिटर्न:**  
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)

### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

लेआउट के लिए मास्टर स्लाइड को लौटाता या सेट करता है। पढ़ें/लिखें [IMasterSlide](../../com.aspose.slides/imasterslide)।

**रिटर्न:**  
[IMasterSlide](../../com.aspose.slides/imasterslide)

### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

लेआउट के लिए मास्टर स्लाइड को लौटाता या सेट करता है। पढ़ें/लिखें [IMasterSlide](../../com.aspose.slides/imasterslide)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

इस लेआउट स्लाइड के लेआउट प्रकार को लौटाता है। केवल पढ़ने योग्य [SlideLayoutType](../../com.aspose.slides/slidelayouttype)।

**रिटर्न:**  
byte

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

यदि इस लेआउट स्लाइड पर निर्भर कम से कम एक स्लाइड मौजूद हो तो true लौटाता है। केवल पढ़ने योग्य boolean।

**रिटर्न:**  
boolean

### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

एक सरणी लौटाता है जिसमें सभी स्लाइडें शामिल हैं, जो इस लेआउट स्लाइड पर निर्भर हैं।

**रिटर्न:**  
com.aspose.slides.ISlide[] - सभी स्लाइडों की सरणी, जो इस लेआउट स्लाइड पर निर्भर हैं

### remove() {#remove--}
```
public abstract void remove()
```

प्रेजेंटेशन से लेआउट हटाता है।

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

लेआउट स्लाइड के लिए ड्राइंग गाइड्स का संग्रह लौटाता है। केवल पढ़ने योग्य [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // स्लाइड केंद्र के बाएँ ओर नया ऊर्ध्वाधर ड्राइंग गाइड जोड़ रहा है
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)