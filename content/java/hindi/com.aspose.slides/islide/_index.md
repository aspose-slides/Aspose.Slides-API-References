---
title: ISlide
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एक प्रस्तुति में स्लाइड का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/islide/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

एक प्रस्तुति में स्लाइड का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | स्लाइड का HeaderFooter प्रबंधक लौटाता है। |
| [getSlideNumber()](#getSlideNumber--) | स्लाइड की संख्या लौटाता है। |
| [setSlideNumber(int value)](#setSlideNumber-int-) | स्लाइड की संख्या लौटाता है। |
| [getHidden()](#getHidden--) | निर्धारित करता है कि निर्दिष्ट स्लाइड स्लाइड शो के दौरान छिपी हुई है या नहीं। |
| [setHidden(boolean value)](#setHidden-boolean-) | निर्धारित करता है कि निर्दिष्ट स्लाइड स्लाइड शो के दौरान छिपी हुई है या नहीं। |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | कस्टम स्केलिंग के साथ एक इमेज ऑब्जेक्ट लौटाता है। |
| [getImage()](#getImage--) | थंबनेल इमेज ऑब्जेक्ट (वास्तविक आकार का 20%) लौटाता है। |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | निर्दिष्ट आकार के साथ इमेज ऑब्जेक्ट लौटाता है। |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | निर्दिष्ट पैरामीटर के साथ थंबनेल TIFF बिटमैप ऑब्जेक्ट लौटाता है। |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | थंबनेल बिटमैप ऑब्जेक्ट लौटाता है। |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | कस्टम स्केलिंग के साथ थंबनेल बिटमैप ऑब्जेक्ट लौटाता है। |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | निर्दिष्ट आकार के साथ थंबनेल बिटमैप ऑब्जेक्ट लौटाता है। |
| [getLayoutSlide()](#getLayoutSlide--) | वर्तमान स्लाइड के लिए लेआउट स्लाइड लौटाता या सेट करता है। |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | वर्तमान स्लाइड के लिए लेआउट स्लाइड लौटाता या सेट करता है। |
| [getNotesSlideManager()](#getNotesSlideManager--) | नोट्स स्लाइड तक पहुँचने, जोड़ने और हटाने की अनुमति देता है। |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | विशिष्ट लेखक द्वारा जोड़े गए सभी स्लाइड टिप्पणी लौटाता है। |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | स्लाइड सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | स्लाइड सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | स्लाइड सामग्री को EMF फ़ाइल के रूप में सहेजता है। |
| [remove()](#remove--) | प्रस्तुति से स्लाइड हटाता है। |
| [reset()](#reset--) | LayoutSlide पर प्रोटोटाइप वाले प्रत्येक शेप की स्थिति, आकार और फ़ॉर्मेटिंग रीसेट करता है। |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

स्लाइड का HeaderFooter प्रबंधक लौटाता है। केवल-पढ़ने योग्य [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)।

**रिटर्न:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

स्लाइड की संख्या लौटाता है। [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) संग्रह में स्लाइड का अनुक्रमणिका हमेशा SlideNumber - 1 के बराबर होता है। पढ़ने/लिखने योग्य int।

**रिटर्न:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

स्लाइड की संख्या लौटाता है। [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) संग्रह में स्लाइड का अनुक्रमणिका हमेशा SlideNumber - 1 के बराबर होता है। पढ़ने/लिखने योग्य int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

निर्धारित करता है कि निर्दिष्ट स्लाइड स्लाइड शो के दौरान छिपी हुई है या नहीं। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

निर्धारित करता है कि निर्दिष्ट स्लाइड स्लाइड शो के दौरान छिपी हुई है या नहीं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

कस्टम स्केलिंग के साथ एक इमेज ऑब्जेक्ट लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scaleX | float | x-अक्ष दिशा में इस थंबनेल को स्केल करने के लिए मान। |
| scaleY | float | y-अक्ष दिशा में इस थंबनेल को स्केल करने के लिए मान। |

**रिटर्न:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

थंबनेल इमेज ऑब्जेक्ट (वास्तविक आकार का 20%) लौटाता है।

**रिटर्न:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage
### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public abstract IImage getImage(Dimension imageSize)
```

निर्दिष्ट आकार के साथ इमेज ऑब्जेक्ट लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageSize | java.awt.Dimension | बनाये जाने वाले इमेज का आकार। |

**रिटर्न:**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

निर्दिष्ट पैरामीटर के साथ थंबनेल TIFF बिटमैप ऑब्जेक्ट लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff विकल्प। |

**रिटर्न:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

थंबनेल बिटमैप ऑब्जेक्ट लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |

**रिटर्न:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

कस्टम स्केलिंग के साथ थंबनेल बिटमैप ऑब्जेक्ट लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |
| scaleX | float | x-अक्ष दिशा में इस थंबनेल को स्केल करने के लिए मान। |
| scaleY | float | y-अक्ष दिशा में इस थंबनेल को स्केल करने के लिए मान। |

**रिटर्न:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage getImage(IRenderingOptions options, Dimension imageSize)
```

निर्दिष्ट आकार के साथ थंबनेल बिटमैप ऑब्जेक्ट लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |
| imageSize | java.awt.Dimension | बनाये जाने वाले इमेज का आकार। |

**रिटर्न:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

वर्तमान स्लाइड के लिए लेआउट स्लाइड लौटाता या सेट करता है। पढ़ने/लिखने योग्य [ILayoutSlide](../../com.aspose.slides/ilayoutslide)।

**रिटर्न:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

वर्तमान स्लाइड के लिए लेआउट स्लाइड लौटाता या सेट करता है। पढ़ने/लिखने योग्य [ILayoutSlide](../../com.aspose.slides/ilayoutslide)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

नोट्स स्लाइड तक पहुँचने, जोड़ने और हटाने की अनुमति देता है। केवल-पढ़ने योग्य [INotesSlideManager](../../com.aspose.slides/inotesslidemanager)।

**रिटर्न:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

विशिष्ट लेखक द्वारा जोड़े गए सभी स्लाइड टिप्पणी लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | खोजने के लिए टिप्पणी लेखक या सभी टिप्पणी लौटाने के लिए null। |

**रिटर्न:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

स्लाइड सामग्री को SVG फ़ाइल के रूप में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | लक्ष्य स्ट्रीम |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

स्लाइड सामग्री को SVG फ़ाइल के रूप में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | लक्ष्य स्ट्रीम |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG जनरेशन विकल्प |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

स्लाइड सामग्री को EMF फ़ाइल के रूप में सहेजता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | लक्ष्य स्ट्रीम |
### remove() {#remove--}
```
public abstract void remove()
```

प्रेज़ेंटेशन से स्लाइड हटाता है।
### reset() {#reset--}
```
public abstract void reset()
```

LayoutSlide पर प्रोटोटाइप वाले प्रत्येक शेप की स्थिति, आकार और फ़ॉर्मेटिंग रीसेट करता है।