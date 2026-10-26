---
title: IZoomObject
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: स्लाइड में एक ज़ूम ऑब्जेक्ट को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/izoomobject/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

एक स्लाइड में Zoom ऑब्जेक्ट को दर्शाता है।
## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getImageType()](#getImageType--) | ज़ूम ऑब्जेक्ट का इमेज प्रकार प्राप्त करता है या सेट करता है। |
| [setImageType(int value)](#setImageType-int-) | ज़ूम ऑब्जेक्ट का इमेज प्रकार प्राप्त करता है या सेट करता है। |
| [getReturnToParent()](#getReturnToParent--) | स्लाइडशो में नेविगेशन व्यवहार प्राप्त करता है या सेट करता है। |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | स्लाइडशो में नेविगेशन व्यवहार प्राप्त करता है या सेट करता है। |
| [getShowBackground()](#getShowBackground--) | यह निर्धारित करने वाले मान को प्राप्त करता है या सेट करता है कि Zoom गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | यह निर्धारित करने वाले मान को प्राप्त करता है या सेट करता है कि Zoom गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। |
| [getZoomImage()](#getZoomImage--) | ज़ूम ऑब्जेक्ट के लिए इमेज प्राप्त करता है या सेट करता है। |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | ज़ूम ऑब्जेक्ट के लिए इमेज प्राप्त करता है या सेट करता है। |
| [getTransitionDuration()](#getTransitionDuration--) | ज़ूम और स्लाइड के बीच ट्रांज़िशन की अवधि प्राप्त करता है या सेट करता है। |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | ज़ूम और स्लाइड के बीच ट्रांज़िशन की अवधि प्राप्त करता है या सेट करता है। |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

ज़ूम ऑब्जेक्ट का इमेज प्रकार प्राप्त करता है या सेट करता है। पढ़ने/लिखने [ZoomImageType](../../com.aspose.slides/zoomimagetype)। डिफ़ॉल्ट मान: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

निर्दिष्ट करता है कि Zoom ऑब्जेक्ट स्लाइड प्रीव्यू या कवर इमेज का उपयोग कर रहा है या नहीं।

**वापसी:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```

ज़ूम ऑब्जेक्ट का इमेज प्रकार प्राप्त करता है या सेट करता है। पढ़ने/लिखने [ZoomImageType](../../com.aspose.slides/zoomimagetype)। डिफ़ॉल्ट मान: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

निर्दिष्ट करता है कि Zoom ऑब्जेक्ट स्लाइड प्रीव्यू या कवर इमेज का उपयोग कर रहा है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

स्लाइडशो में नेविगेशन व्यवहार प्राप्त करता है या सेट करता है। पढ़ने/लिखने boolean। डिफ़ॉल्ट मान: false

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

सत्य मान यह प्रॉपर्टी स्लाइडशो में पैरेंट नेविगेशन व्यवहार को वापस लौटने को निर्दिष्ट करती है।

**वापसी:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

स्लाइडशो में नेविगेशन व्यवहार प्राप्त करता है या सेट करता है। पढ़ने/लिखने boolean। डिफ़ॉल्ट मान: false

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

सत्य मान यह प्रॉपर्टी स्लाइडशो में पैरेंट नेविगेशन व्यवहार को वापस लौटने को निर्दिष्ट करती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

यह निर्धारित करने वाले मान को प्राप्त करता है या सेट करता है कि Zoom गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। पढ़ने/लिखने boolean। डिफ़ॉल्ट मान: true

--------------------

> ```
> The example demonstrates removing the background of an image of a Zoom object:
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
public abstract void setShowBackground(boolean value)
```

यह निर्धारित करने वाले मान को प्राप्त करता है या सेट करता है कि Zoom गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं। पढ़ने/लिखने boolean। डिफ़ॉल्ट मान: true

--------------------

> ```
> The example demonstrates removing the background of an image of a Zoom object:
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
public abstract IPPImage getZoomImage()
```

ज़ूम ऑब्जेक्ट के लिए इमेज प्राप्त करता है या सेट करता है। पढ़ने/लिखने [IPPImage](../../com.aspose.slides/ippimage)।

--------------------

> ```
> The example demonstrates changing an image of a Zoom object:
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


**वापसी:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```

ज़ूम ऑब्जेक्ट के लिए इमेज प्राप्त करता है या सेट करता है। पढ़ने/लिखने [IPPImage](../../com.aspose.slides/ippimage)।

--------------------

> ```
> उदाहरण दर्शाता है कि Zoom ऑब्जेक्ट की छवि को कैसे बदला जाए:
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
public abstract float getTransitionDuration()
```

ज़ूम और स्लाइड के बीच ट्रांज़िशन की अवधि प्राप्त करता है या सेट करता है। पढ़ने/लिखने float। डिफ़ॉल्ट मान: 1.0f

--------------------

> ```
> the example demonstrates changing the duration of the transition between Zoom and slide:
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

यदि निर्दिष्ट नहीं किया गया (TransitionDur = 0), तो यह गंतव्य स्लाइड के ट्रांज़िशन और उस ट्रांज़िशन से संबंधित टाइमिंग का उपयोग करेगा।

**वापसी:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

ज़ूम और स्लाइड के बीच ट्रांज़िशन की अवधि प्राप्त करता है या सेट करता है। पढ़ने/लिखने float। डिफ़ॉल्ट मान: 1.0f

--------------------

> ```
> यह उदाहरण ज़ूम और स्लाइड के बीच ट्रांज़िशन की अवधि को बदलने का प्रदर्शन करता है:
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

यदि निर्दिष्ट नहीं किया गया (TransitionDur = 0), तो यह गंतव्य स्लाइड के ट्रांज़िशन और उस ट्रांज़िशन से संबंधित टाइमिंग का उपयोग करेगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |