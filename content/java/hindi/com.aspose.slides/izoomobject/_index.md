---
title: IZoomObject
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एक स्लाइड में Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/izoomobject/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

एक स्लाइड में Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getImageType()](#getImageType--) | Zoom ऑब्जेक्ट का इमेज प्रकार प्राप्त या सेट करता है। |
| [setImageType(int value)](#setImageType-int-) | Zoom ऑब्जेक्ट का इमेज प्रकार प्राप्त या सेट करता है। |
| [getReturnToParent()](#getReturnToParent--) | स्लाइडशो में नेविगेशन व्यवहार को प्राप्त या सेट करता है। |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | स्लाइडशो में नेविगेशन व्यवहार को प्राप्त या सेट करता है। |
| [getShowBackground()](#getShowBackground--) | निर्धारित करने वाला मान कि Zoom गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं, इसे प्राप्त या सेट करता है। |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | निर्धारित करने वाला मान कि Zoom गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं, इसे प्राप्त या सेट करता है। |
| [getZoomImage()](#getZoomImage--) | Zoom ऑब्जेक्ट की छवि को प्राप्त या सेट करता है। |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Zoom ऑब्जेक्ट की छवि को प्राप्त या सेट करता है। |
| [getTransitionDuration()](#getTransitionDuration--) | Zoom और स्लाइड के बीच ट्रांज़िशन की अवधि को प्राप्त या सेट करता है। |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Zoom और स्लाइड के बीच ट्रांज़िशन की अवधि को प्राप्त या सेट करता है। |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

Zoom ऑब्जेक्ट का इमेज प्रकार प्राप्त या सेट करता है। पढ़ें/लिखें [ZoomImageType](../../com.aspose.slides/zoomimagetype)। डिफ़ॉल्ट मान: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

**रिटर्न:**  
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```

Zoom ऑब्जेक्ट का इमेज प्रकार प्राप्त या सेट करता है। पढ़ें/लिखें [ZoomImageType](../../com.aspose.slides/zoomimagetype)। डिफ़ॉल्ट मान: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
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

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

स्लाइडशो में नेविगेशन व्यवहार को प्राप्त या सेट करता है। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान: false

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

प्रॉपर्टी का true मान स्लाइडशो में पैरेंट में लौटने वाले नेविगेशन व्यवहार को निर्दिष्ट करता है।

**रिटर्न:**  
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

स्लाइडशो में नेविगेशन व्यवहार को प्राप्त या सेट करता है। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान: false

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

प्रॉपर्टी का true मान स्लाइडशो में पैरेंट में लौटने वाले नेविगेशन व्यवहार को निर्दिष्ट करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

निर्धारित करने वाला मान कि Zoom गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं, इसे प्राप्त या सेट करता है। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान: true

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


**रिटर्न:**  
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public abstract void setShowBackground(boolean value)
```

निर्धारित करने वाला मान कि Zoom गंतव्य स्लाइड की पृष्ठभूमि का उपयोग करेगा या नहीं, इसे प्राप्त या सेट करता है। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान: true

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

Zoom ऑब्जेक्ट की छवि को प्राप्त या सेट करता है। पढ़ें/लिखें [IPPImage](../../com.aspose.slides/ippimage)।

--------------------

> ```
> The example demonstrates changing an image of a Zoom object:
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

**रिटर्न:**  
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```

Zoom ऑब्जेक्ट की छवि को प्राप्त या सेट करता है। पढ़ें/लिखें [IPPImage](../../com.aspose.slides/ippimage)।

--------------------

> ```
> The example demonstrates changing an image of a Zoom object:
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

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```

Zoom और स्लाइड के बीच ट्रांज़िशन की अवधि को प्राप्त या सेट करता है। पढ़ें/लिखें float। डिफ़ॉल्ट मान: 1.0f

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

यदि निर्दिष्ट नहीं किया गया है (TransitionDur = 0), तो यह गंतव्य स्लाइड ट्रांज़िशन और उस ट्रांज़िशन से जुड़े समय मानों का उपयोग करेगा।

**रिटर्न:**  
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

Zoom और स्लाइड के बीच ट्रांज़िशन की अवधि को प्राप्त या सेट करता है। पढ़ें/लिखें float। डिफ़ॉल्ट मान: 1.0f

--------------------

> ```
> उदाहरण दिखाता है कि Zoom और स्लाइड के बीच ट्रांज़िशन की अवधि कैसे बदलें:
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

यदि निर्दिष्ट नहीं किया गया है (TransitionDur = 0), तो यह गंतव्य स्लाइड ट्रांज़िशन और उस ट्रांज़िशन से जुड़े समय मानों का उपयोग करेगा।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |