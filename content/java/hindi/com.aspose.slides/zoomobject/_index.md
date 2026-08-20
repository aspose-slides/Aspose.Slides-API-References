---
title: ZoomObject
second_title: जावा के लिए Aspose.Slides API संदर्भ
description: स्लाइड में एक Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/zoomobject/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**सभी लागू किए गए इंटरफ़ेस:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

स्लाइड में एक Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getImageType()](#getImageType--) | जूम ऑब्जेक्ट की इमेज प्रकार प्राप्त करता है या सेट करता है। |
| [setImageType(int value)](#setImageType-int-) | जूम ऑब्जेक्ट की इमेज प्रकार प्राप्त करता है या सेट करता है। |
| [getReturnToParent()](#getReturnToParent--) | स्लाइडशो में नेविगेशन व्यवहार प्राप्त करता है या सेट करता है। |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | स्लाइडशो में नेविगेशन व्यवहार प्राप्त करता है या सेट करता है। |
| [getShowBackground()](#getShowBackground--) | यह निर्धारित करने वाला मान प्राप्त करता है या सेट करता है कि Zoom गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | यह निर्धारित करने वाला मान प्राप्त करता है या सेट करता है कि Zoom गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। |
| [getZoomImage()](#getZoomImage--) | जूम ऑब्जेक्ट के लिए इमेज प्राप्त करता है या सेट करता है। |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | जूम ऑब्जेक्ट के लिए इमेज प्राप्त करता है या सेट करता है। |
| [getTransitionDuration()](#getTransitionDuration--) | Zoom और स्लाइड के बीच ट्रांज़िशन की अवधि प्राप्त करता है या सेट करता है। |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Zoom और स्लाइड के बीच ट्रांज़िशन की अवधि प्राप्त करता है या सेट करता है। |
### getImageType() {#getImageType--}
```
public final int getImageType()
```

जूम ऑब्जेक्ट की इमेज प्रकार प्राप्त करता है या सेट करता है। पढ़ें/लिखें [ZoomImageType](../../com.aspose.slides/zoomimagetype)। डिफ़ॉल्ट मान: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

निर्दिष्ट करता है कि Zoom ऑब्जेक्ट स्लाइड प्रीव्यू या कवर इमेज का उपयोग कर रहा है या नहीं।

**वापसी:**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

जूम ऑब्जेक्ट की इमेज प्रकार प्राप्त करता है या सेट करता है। पढ़ें/लिखें [ZoomImageType](../../com.aspose.slides/zoomimagetype)। डिफ़ॉल्ट मान: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>      zoomFrame.setImageType(ZoomImageType.Preview);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

निर्दिष्ट करता है कि Zoom ऑब्जेक्ट स्लाइड प्रीव्यू या कवर इमेज का उपयोग कर रहा है या नहीं।

**परामितर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

स्लाइडशो में नेविगेशन व्यवहार प्राप्त करता है या सेट करता है। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान: false

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

प्रॉपर्टी का true मान स्लाइडशो में पेरेंट नेविगेशन व्यवहार को निर्दिष्ट करता है।

**वापसी:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

स्लाइडशो में नेविगेशन व्यवहार प्राप्त करता है या सेट करता है। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान: false

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

प्रॉपर्टी का true मान स्लाइडशो में पेरेंट नेविगेशन व्यवहार को निर्दिष्ट करता है।

**परामितर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```

यह निर्धारित करने वाला मान प्राप्त करता है या सेट करता है कि Zoom गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान: true

--------------------

> ```
> the example demonstrates removing the background of an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public final void setShowBackground(boolean value)
```

यह निर्धारित करने वाला मान प्राप्त करता है या सेट करता है कि Zoom गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान: true

--------------------

> ```
> the example demonstrates removing the background of an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामितर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getZoomImage() {#getZoomImage--}
```
public final IPPImage getZoomImage()
```

जूम ऑब्जेक्ट के लिए इमेज प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IPPImage](../../com.aspose.slides/ippimage)।

--------------------

> ```
> the example demonstrates changing an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      zoomFrame.setImage(image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```

जूम ऑब्जेक्ट के लिए इमेज प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IPPImage](../../com.aspose.slides/ippimage)।

--------------------

> ```
> the example demonstrates changing an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      zoomFrame.setImage(image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामितर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getTransitionDuration() {#getTransitionDuration--}
```
public final float getTransitionDuration()
```

Zoom और स्लाइड के बीच ट्रांज़िशन की अवधि प्राप्त करता है या सेट करता है। पढ़ें/लिखें float। डिफ़ॉल्ट मान: 1.0f

--------------------

> ```
> यह उदाहरण Zoom और स्लाइड के बीच ट्रांज़िशन की अवधि बदलने को दर्शाता है:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

यदि निर्दिष्ट नहीं किया गया (TransitionDur = 0), तो यह गंतव्य स्लाइड ट्रांज़िशन और उस ट्रांज़िशन से जुड़े टाइमिंग्स का उपयोग करेगा।

**वापसी:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```

Zoom और स्लाइड के बीच ट्रांज़िशन की अवधि प्राप्त करता है या सेट करता है। पढ़ें/लिखें float। डिफ़ॉल्ट मान: 1.0f

--------------------

> ```
> यह उदाहरण Zoom और स्लाइड के बीच ट्रांज़िशन की अवधि बदलने को दर्शाता है:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

यदि निर्दिष्ट नहीं किया गया (TransitionDur = 0), तो यह गंतव्य स्लाइड ट्रांज़िशन और उस ट्रांज़िशन से जुड़े टाइमिंग्स का उपयोग करेगा।

**परामितर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |