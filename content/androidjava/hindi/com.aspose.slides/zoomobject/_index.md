---
title: ZoomObject
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: स्लाइड में Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/zoomobject/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

एक स्लाइड में Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getImageType()](#getImageType--) | Zoom ऑब्जेक्ट की इमेज प्रकार को प्राप्त करता है या सेट करता है। |
| [setImageType(int value)](#setImageType-int-) | Zoom ऑब्जेक्ट की इमेज प्रकार को प्राप्त करता है या सेट करता है। |
| [getReturnToParent()](#getReturnToParent--) | स्लाइडशो में नेविगेशन व्यवहार को प्राप्त करता है या सेट करता है। |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | स्लाइडशो में नेविगेशन व्यवहार को प्राप्त करता है या सेट करता है। |
| [getShowBackground()](#getShowBackground--) | यह निर्धारित करने वाला मान प्राप्त करता है या सेट करता है कि Zoom गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | यह निर्धारित करने वाला मान प्राप्त करता है या सेट करता है कि Zoom गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। |
| [getZoomImage()](#getZoomImage--) | Zoom ऑब्जेक्ट के लिए इमेज प्राप्त करता है या सेट करता है। |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Zoom ऑब्जेक्ट के लिए इमेज प्राप्त करता है या सेट करता है। |
| [getTransitionDuration()](#getTransitionDuration--) | Zoom और स्लाइड के बीच ट्रांज़िशन की अवधि प्राप्त करता है या सेट करता है। |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Zoom और स्लाइड के बीच ट्रांज़िशन की अवधि प्राप्त करता है या सेट करता है। |
### getImageType() {#getImageType--}
```
public final int getImageType()
```

Zoom ऑब्जेक्ट की इमेज प्रकार को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [ZoomImageType](../../com.aspose.slides/zoomimagetype)। डिफ़ॉल्ट मान: Preview

--------------------

> ```
> अगला उदाहरण Image Type को Preview मान में बदलने का प्रदर्शन करता है। 
>  इस मामले में Zoom ऑब्जेक्ट की वर्तमान इमेज स्लाइड इमेज में बदल जाती है:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

निर्दिष्ट करता है कि क्या Zoom ऑब्जेक्ट स्लाइड प्रीव्यू या कवर इमेज का उपयोग कर रहा है।

**रिटर्न:**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

Zoom ऑब्जेक्ट की इमेज प्रकार को प्राप्त करता है या सेट करता है। पढ़ें/लिखें [ZoomImageType](../../com.aspose.slides/zoomimagetype)। डिफ़ॉल्ट मान: Preview

--------------------

> ```
> अगला उदाहरण Image Type को Preview मान में बदलने का प्रदर्शन करता है। 
>  इस मामले में Zoom ऑब्जेक्ट की वर्तमान इमेज स्लाइड इमेज में बदल जाती है:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

निर्दिष्ट करता है कि क्या Zoom ऑब्जेक्ट स्लाइड प्रीव्यू या कवर इमेज का उपयोग कर रहा है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

स्लाइडशो में नेविगेशन व्यवहार को प्राप्त करता है या सेट करता है। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान: false

--------------------

> ```
> उदाहरण:
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

संपत्ति का true मान स्लाइडशो में पैरेंट में लौटने वाले नेविगेशन व्यवहार को निर्दिष्ट करता है।

**रिटर्न:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

स्लाइडशो में नेविगेशन व्यवहार को प्राप्त करता है या सेट करता है। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान: false

--------------------

> ```
> उदाहरण:
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

संपत्ति का true मान स्लाइडशो में पैरेंट में लौटने वाले नेविगेशन व्यवहार को निर्दिष्ट करता है।

**पैरामीटर:**
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
> उदाहरण Zoom ऑब्जेक्ट की इमेज की पृष्ठभूमि हटाने को दर्शाता है:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public final void setShowBackground(boolean value)
```

यह निर्धारित करने वाला मान प्राप्त करता है या सेट करता है कि Zoom गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान: true

--------------------

> ```
> उदाहरण Zoom ऑब्जेक्ट की इमेज की पृष्ठभूमि हटाने को दर्शाता है:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public final IPPImage getZoomImage()
```

Zoom ऑब्जेक्ट के लिए इमेज प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IPPImage](../../com.aspose.slides/ippimage)।

--------------------

> ```
> उदाहरण Zoom ऑब्जेक्ट की इमेज बदलने को दर्शाता है:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```

Zoom ऑब्जेक्ट के लिए इमेज प्राप्त करता है या सेट करता है। पढ़ें/लिखें [IPPImage](../../com.aspose.slides/ippimage)।

--------------------

> ```
> उदाहरण Zoom ऑब्जेक्ट की इमेज बदलने को दर्शाता है:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
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
> उदाहरण Zoom और स्लाइड के बीच ट्रांज़िशन की अवधि बदलने को दर्शाता है:
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

यदि निर्दिष्ट नहीं किया गया (TransitionDur = 0), तो यह गंतव्य स्लाइड ट्रांज़िशन और उस ट्रांज़िशन से जुड़े टाइमिंग का उपयोग करेगा।

**रिटर्न:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```

Zoom और स्लाइड के बीच ट्रांज़िशन की अवधि प्राप्त करता है या सेट करता है। पढ़ें/लिखें float। डिफ़ॉल्ट मान: 1.0f

--------------------

> ```
> उदाहरण Zoom और स्लाइड के बीच ट्रांज़िशन की अवधि बदलने को दर्शाता है:
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

यदि निर्दिष्ट नहीं किया गया (TransitionDur = 0), तो यह गंतव्य स्लाइड ट्रांज़िशन और उस ट्रांज़िशन से जुड़े टाइमिंग का उपयोग करेगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |