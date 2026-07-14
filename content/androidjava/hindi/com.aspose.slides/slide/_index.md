---
title: Slide
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक प्रस्तुति में स्लाइड का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/slide/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**सभी लागू इंटरफेस:**
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

एक प्रस्तुति में स्लाइड का प्रतिनिधित्व करता है।

## विधियां

| विधि | विवरण |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | स्लाइड का HeaderFooter प्रबंधक लौटाता है। |
| [getThemeManager()](#getThemeManager--) | ओवरराइडिंग थीम प्रबंधक लौटाता है। |
| [getSlideNumber()](#getSlideNumber--) | स्लाइड की संख्या लौटाता है। |
| [setSlideNumber(int value)](#setSlideNumber-int-) | स्लाइड की संख्या लौटाता है। |
| [getHidden()](#getHidden--) | स्लाइड शो के दौरान निर्दिष्ट स्लाइड छिपी हुई है या नहीं, निर्धारित करता है। |
| [setHidden(boolean value)](#setHidden-boolean-) | स्लाइड शो के दौरान निर्दिष्ट स्लाइड छिपी हुई है या नहीं, निर्धारित करता है। |
| [getShowMasterShapes()](#getShowMasterShapes--) | मास्टर स्लाइड पर आकृतियों को स्लाइड पर दिखाया जाए या न दिखाया जाए, निर्धारित करता है। |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | मास्टर स्लाइड पर आकृतियों को स्लाइड पर दिखाया जाए या न दिखाया जाए, निर्धारित करता है। |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | कस्टम स्केलिंग के साथ थंबनेल इमेज ऑब्जेक्ट लौटाता है। |
| [getImage()](#getImage--) | थंबनेल इमेज ऑब्जेक्ट (वास्तविक आकार के 20 %) लौटाता है। |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | निर्दिष्ट आकार के साथ थंबनेल इमेज ऑब्जेक्ट लौटाता है। |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | निर्दिष्ट पैरामीटर के साथ थंबनेल TIFF इमेज ऑब्जेक्ट लौटाता है। |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | थंबनेल इमेज ऑब्जेक्ट लौटाता है। |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | कस्टम स्केलिंग के साथ थंबनेल इमेज ऑब्जेक्ट लौटाता है। |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | निर्दिष्ट आकार के साथ थंबनेल इमेज ऑब्जेक्ट लौटाता है। |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | स्लाइड सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | स्लाइड सामग्री को SVG फ़ाइल के रूप में सहेजता है। |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | स्लाइड सामग्री को EMF फ़ाइल के रूप में सहेजता है। |
| [remove()](#remove--) | प्रस्तुति से स्लाइड हटाता है। |
| [getLayoutSlide()](#getLayoutSlide--) | वर्तमान स्लाइड के लिए लेआउट स्लाइड लौटाता है या सेट करता है। |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | वर्तमान स्लाइड के लिए लेआउट स्लाइड लौटाता है या सेट करता है। |
| [reset()](#reset--) | LayoutSlide पर प्रोटोटाइप वाली प्रत्येक आकृति की स्थिति, आकार और फ़ॉर्मेट रीसेट करता है। |
| [getNotesSlideManager()](#getNotesSlideManager--) | नोट्स स्लाइड तक पहुँच, जोड़ और हटाने की अनुमति देता है। |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | विशिष्ट लेखक द्वारा जोड़े गए सभी स्लाइड टिप्पणियाँ लौटाता है। |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | सभी अनुमत आकृतियों में सभी पैराग्राफ़ के रन को समान फ़ॉर्मेटिंग के साथ जोड़ता है। |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

स्लाइड का HeaderFooter प्रबंधक लौटाता है। केवल पढ़ने योग्य [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)।

**वापसी:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

ओवरराइडिंग थीम प्रबंधक लौटाता है। केवल पढ़ने योग्य [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)।

**वापसी:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

स्लाइड की संख्या लौटाता है। [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) संग्रह में स्लाइड का अनुक्रमांक हमेशा SlideNumber - Presentation.FirstSlideNumber के बराबर होता है। पढ़ने/लिखने योग्य int।

**वापसी:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

स्लाइड की संख्या सेट करता है। [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) संग्रह में स्लाइड का अनुक्रमांक हमेशा SlideNumber - Presentation.FirstSlideNumber के बराबर होता है। पढ़ने/लिखने योग्य int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

निर्धारित करता है कि स्लाइड शो के दौरान निर्दिष्ट स्लाइड छिपी हुई है या नहीं। पढ़ने/लिखने योग्य boolean।

**वापसी:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

निर्धारित करता है कि स्लाइड शो के दौरान निर्दिष्ट स्लाइड छिपी हुई है या नहीं। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

मास्टर स्लाइड पर आकृतियों को स्लाइड पर दिखाया जाए या न दिखाया जाए, निर्धारित करता है। पढ़ने/लिखने योग्य boolean।

**वापसी:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

मास्टर स्लाइड पर आकृतियों को स्लाइड पर दिखाया जाए या न दिखाया जाए, निर्धारित करता है। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

कस्टम स्केलिंग के साथ थंबनेल इमेज ऑब्जेक्ट लौटाता है।

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // पहले स्लाइड तक पहुँचें
>      ISlide sld = pres.getSlides().get_Item(0);
>      // पूर्ण स्केल छवि बनाएं
>      IImage bmp = sld.getImage(1f, 1f);
>      // छवि को JPEG फ़ॉर्मेट में डिस्क पर सहेजें
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // प्रस्तुति में पहली स्लाइड को Bitmap ऑब्जेक्ट में रूपांतरित करता है
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // छवि को PNG फ़ॉर्मेट में सहेजता है
>      bmp.save("Slide_0.png", ImageFormat.Png);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.ppt");
>  try {
>      for (ISlide sld : pres.getSlides())
>      {
>          // पूर्ण स्केल छवि बनाएं
>          IImage bmp = sld.getImage(1f, 1f);
>          // छवि को JPEG फ़ॉर्मेट में डिस्क पर सहेजें
>          bmp.save("Slide_"+sld.getSlideNumber()+"0.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG with customized dimensions.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.pptx");
>  try {
>      // आयाम निर्धारित करें
>      int desiredX = 1200;
>      int desiredY = 800;
>      // X और Y के स्केल किए हुए मान प्राप्त करें
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // पूर्ण स्केल छवि बनाएं
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // छवि को JPEG फ़ॉर्मेट में डिस्क पर सहेजें
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scaleX | float | X-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |
| scaleY | float | Y-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |

**वापसी:**
[IImage](../../com.aspose.slides/iimage) - IImage ऑब्जेक्ट।

### getImage() {#getImage--}
```
public final IImage getImage()
```

थंबनेल इमेज ऑब्जेक्ट (वास्तविक आकार के 20 %) लौटाता है।

**वापसी:**
[IImage](../../com.aspose.slides/iimage)

### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public final IImage getImage(Size imageSize)
```

निर्दिष्ट आकार के साथ थंबनेल इमेज ऑब्जेक्ट लौटाता है।

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // प्रस्तुति में पहली स्लाइड को निर्दिष्ट आकार के साथ Bitmap में परिवर्तित करता है
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new com.aspose.slides.android.Size(1820, 1040));
>      // छवि को JPEG फ़ॉर्मेट में सहेजता है
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | बनाइ जाने वाली छवि का आकार। |

**वापसी:**
[IImage](../../com.aspose.slides/iimage) - Image ऑब्जेक्ट।

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

निर्दिष्ट पैरामीटर के साथ थंबनेल TIFF इमेज ऑब्जेक्ट लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | TIFF विकल्प। |

**वापसी:**
[IImage](../../com.aspose.slides/iimage) - Image ऑब्जेक्ट।

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

थंबनेल इमेज ऑब्जेक्ट लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |

**वापसी:**
[IImage](../../com.aspose.slides/iimage) - Image ऑब्जेक्ट।

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

कस्टम स्केलिंग के साथ थंबनेल इमेज ऑब्जेक्ट लौटाता है।

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // रेंडरिंग विकल्प बनाएं
>      IRenderingOptions options = new RenderingOptions();
>      // नोट्स और कमेंट्स लेआउट विकल्प बनाएं
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // पेज पर नोट्स की स्थिति सेट करता है
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // पेज पर कमेंट्स की स्थिति सेट करता है
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // कमेंट आउटपुट क्षेत्र की चौड़ाई सेट करता है
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // कमेंट क्षेत्र के लिए रंग सेट करता है
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // रेंडरिंग के लिए लेआउट विकल्प सेट करें
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // प्रेजेंटेशन की पहली स्लाइड को android.graphics.Bitmap ऑब्जेक्ट में परिवर्तित करता है
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // छवि को GIF फ़ॉर्मेट में सहेजता है
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |
| scaleX | float | X-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |
| scaleY | float | Y-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |

**वापसी:**
[IImage](../../com.aspose.slides/iimage) - Bitmap ऑब्जेक्ट।

### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage getImage(IRenderingOptions options, Size imageSize)
```

निर्दिष्ट आकार के साथ थंबनेल इमेज ऑब्जेक्ट लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |
| imageSize | [Size](../../com.aspose.slides.android/size) | बनाइ जाने वाली छवि का आकार। |

**वापसी:**
[IImage](../../com.aspose.slides/iimage) - Image ऑब्जेक्ट।

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

स्लाइड सामग्री को SVG फ़ाइल के रूप में सहेजता है।

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // पहली स्लाइड को SVG फ़ाइल के रूप में सहेजता है
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | लक्ष्य स्ट्रीम |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

स्लाइड सामग्री को SVG फ़ाइल के रूप में सहेजता है।

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // पहली स्लाइड को SVG फ़ाइल के रूप में सहेजता है
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | लक्ष्य स्ट्रीम |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG जनरेशन विकल्प |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

स्लाइड सामग्री को EMF फ़ाइल के रूप में सहेजता है।

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // पहली स्लाइड को एक मेटा फ़ाइल के रूप में सहेजता है
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | लक्ष्य स्ट्रीम |

### remove() {#remove--}
```
public final void remove()
```

प्रस्तुति से स्लाइड हटाता है।

### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

वर्तमान स्लाइड के लिए लेआउट स्लाइड लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [ILayoutSlide](../../com.aspose.slides/ilayoutslide)।

**वापसी:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

वर्तमान स्लाइड के लिए लेआउट स्लाइड लौटाता है या सेट करता है। पढ़ने/लिखने योग्य [ILayoutSlide](../../com.aspose.slides/ilayoutslide)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### reset() {#reset--}
```
public final void reset()
```

LayoutSlide पर प्रोटोटाइप वाली प्रत्येक आकृति की स्थिति, आकार और फ़ॉर्मेट रीसेट करता है।

### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

नोट्स स्लाइड तक पहुँच, जोड़ और हटाने की अनुमति देता है। केवल पढ़ने योग्य [INotesSlideManager](../../com.aspose.slides/inotesslidemanager)।

**वापसी:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

विशिष्ट लेखक द्वारा जोड़े गए सभी स्लाइड टिप्पणियाँ लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | खोजने के लिए टिप्पणी लेखक या सभी टिप्पणियाँ लौटाने के लिए null। |

**वापसी:**
com.aspose.slides.IComment[] - [Comment](../../com.aspose.slides/comment) की एरे।

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

सभी अनुमत आकृतियों में सभी पैराग्राफ़ के रन को समान फ़ॉर्मेटिंग के साथ जोड़ता है।