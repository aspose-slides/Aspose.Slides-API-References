---
title: PictureFillFormat
second_title: Aspose.Slides for Android हेतु जावा API रेफ़रेंस
description: एक चित्र भराव शैली का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/picturefillformat/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**  
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)  
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

चित्र भराव शैली का प्रतिनिधित्व करता है।

## विधियां

| विधि | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | चित्र को भरने के लिए उपयोग किए जाने वाले डीपीआई को प्राप्त करता है या सेट करता है। |
| [setDpi(int value)](#setDpi-int-) | चित्र को भरने के लिए उपयोग किए जाने वाले डीपीआई को प्राप्त करता है या सेट करता है। |
| [getPictureFillMode()](#getPictureFillMode--) | चित्र भराव मोड को प्राप्त करता है या सेट करता है। |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | चित्र भराव मोड को प्राप्त करता है या सेट करता है। |
| [getPicture()](#getPicture--) | चित्र को प्राप्त करता है। |
| [getCropLeft()](#getCropLeft--) | वास्तविक छवि की चौड़ाई के प्रतिशत को प्राप्त करता है या सेट करता है जो चित्र के बाएँ तरफ़ से काटा जाता है। |
| [setCropLeft(float value)](#setCropLeft-float-) | वास्तविक छवि की चौड़ाई के प्रतिशत को प्राप्त करता है या सेट करता है जो चित्र के बाएँ तरफ़ से काटा जाता है। |
| [getCropTop()](#getCropTop--) | वास्तविक छवि की ऊँचाई के प्रतिशत को प्राप्त करता है या सेट करता है जो चित्र के ऊपर से काटा जाता है। |
| [setCropTop(float value)](#setCropTop-float-) | वास्तविक छवि की ऊँचाई के प्रतिशत को प्राप्त करता है या सेट करता है जो चित्र के ऊपर से काटा जाता है। |
| [getCropRight()](#getCropRight--) | वास्तविक छवि की चौड़ाई के प्रतिशत को प्राप्त करता है या सेट करता है जो चित्र के दाएँ तरफ़ से काटा जाता है। |
| [setCropRight(float value)](#setCropRight-float-) | वास्तविक छवि की चौड़ाई के प्रतिशत को प्राप्त करता है या सेट करता है जो चित्र के दाएँ तरफ़ से काटा जाता है। |
| [getCropBottom()](#getCropBottom--) | वास्तविक छवि की ऊँचाई के प्रतिशत को प्राप्त करता है या सेट करता है जो चित्र के नीचे से काटा जाता है। |
| [setCropBottom(float value)](#setCropBottom-float-) | वास्तविक छवि की ऊँचाई के प्रतिशत को प्राप्त करता है या सेट करता है जो चित्र के नीचे से काटा जाता है। |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | भराव चित्र के कटे-हुए क्षेत्रों को हटाता है। |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | आकार और निर्दिष्ट रिज़ॉल्यूशन के आधार पर छवि का आकार कम करके उसे संकुचित करता है। |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | आकार और निर्दिष्ट रिज़ॉल्यूशन के आधार पर छवि का आकार कम करके उसे संकुचित करता है। |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | आकार की बाउंडिंग बॉक्स के बाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के बाएँ किनारे को प्राप्त करता है या सेट करता है। |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | आकार की बाउंडिंग बॉक्स के बाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के बाएँ किनारे को प्राप्त करता है या सेट करता है। |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | आकार की बाउंडिंग बॉक्स के ऊपर किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के ऊपर किनारे को प्राप्त करता है या सेट करता है। |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | आकार की बाउंडिंग बॉक्स के ऊपर किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के ऊपर किनारे को प्राप्त करता है या सेट करता है। |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | आकार की बाउंडिंग बॉक्स के दाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के दाएँ किनारे को प्राप्त करता है या सेट करता है। |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | आकार की बाउंडिंग बॉक्स के दाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के दाएँ किनारे को प्राप्त करता है या सेट करता है। |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | आकार की बाउंडिंग बॉक्स के नीचे किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के नीचे किनारे को प्राप्त करता है या सेट करता है। |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | आकार की बाउंडिंग बॉक्स के नीचे किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के नीचे किनारे को प्राप्त करता है या सेट करता है। |
| [getTileOffsetX()](#getTileOffsetX--) | आकार की उत्पत्ति बिंदु से टेक्सचर के क्षैतिज ऑफ़सेट को पॉइंट्स में प्राप्त करता है या सेट करता है। |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | आकार की उत्पत्ति बिंदु से टेक्सचर के क्षैतिज ऑफ़सेट को पॉइंट्स में प्राप्त करता है या सेट करता है। |
| [getTileOffsetY()](#getTileOffsetY--) | आकार की उत्पत्ति बिंदु से टेक्सचर के लंबवत ऑफ़सेट को पॉइंट्स में प्राप्त करता है या सेट करता है। |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | आकार की उत्पत्ति बिंदु से टेक्सचर के लंबवत ऑफ़सेट को पॉइंट्स में प्राप्त करता है या सेट करता है। |
| [getTileScaleX()](#getTileScaleX--) | प्रतिशत के रूप में टेक्सचर भराव के लिए क्षैतिज स्केल को प्राप्त करता है या सेट करता है। |
| [setTileScaleX(float value)](#setTileScaleX-float-) | प्रतिशत के रूप में टेक्सचर भराव के लिए क्षैतिज स्केल को प्राप्त करता है या सेट करता है। |
| [getTileScaleY()](#getTileScaleY--) | प्रतिशत के रूप में टेक्सचर भराव के लिए लंबवत स्केल को प्राप्त करता है या सेट करता है। |
| [setTileScaleY(float value)](#setTileScaleY-float-) | प्रतिशत के रूप में टेक्सचर भराव के लिए लंबवत स्केल को प्राप्त करता है या सेट करता है। |
| [getTileAlignment()](#getTileAlignment--) | आकार के भीतर टेक्सचर की संरेखण को प्राप्त करता है या सेट करता है। |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | आकार के भीतर टेक्सचर की संरेखण को प्राप्त करता है या सेट करता है। |
| [getTileFlip()](#getTileFlip--) | टेक्सचर टाइल को उसके क्षैतिज, लंबवत या दोनों अक्षों के चारों ओर उलटता है। |
| [setTileFlip(int value)](#setTileFlip-int-) | टेक्सचर टाइल को उसका क्षैतिज, लंबवत या दोनों अक्षों के चारों ओर उलटता है। |

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने-योग्य long.

**वापसी:**  
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

चित्र को भरने के लिए उपयोग किए जाने वाले डीपीआई को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य int।

**वापसी:**  
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

चित्र को भरने के लिए उपयोग किए जाने वाले डीपीआई को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य int।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

चित्र भराव मोड को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [PictureFillMode](../../com.aspose.slides/picturefillmode)।

**वापसी:**  
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

चित्र भराव मोड को प्राप्त करता है या सेट करता है। पढ़ने/लिखने योग्य [PictureFillMode](../../com.aspose.slides/picturefillmode)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

चित्र को प्राप्त करता है। केवल-पढ़ने-योग्य [ISlidesPicture](../../com.aspose.slides/islidespicture)।

**वापसी:**  
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

वास्तविक छवि की चौड़ाई के प्रतिशत को प्राप्त करता है या सेट करता है जो चित्र के बाएँ तरफ़ से काटा जाता है। पढ़ने/लिखने योग्य float।

**वापसी:**  
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

वास्तविक छवि की चौड़ाई के प्रतिशत को प्राप्त करता है या सेट करता है जो चित्र के बाएँ तरफ़ से काटा जाता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

वास्तविक छवि की ऊँचाई के प्रतिशत को प्राप्त करता है या सेट करता है जो चित्र के ऊपर से काटा जाता है। पढ़ने/लिखने योग्य float।

**वापसी:**  
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

वास्तविक छवि की ऊँचाई के प्रतिशत को प्राप्त करता है या सेट करता है जो चित्र के ऊपर से काटा जाता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

वास्तविक छवि की चौड़ाई के प्रतिशत को प्राप्त करता है या सेट करता है जो चित्र के दाएँ तरफ़ से काटा जाता है। पढ़ने/लिखने योग्य float।

**वापसी:**  
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

वास्तविक छवि की चौड़ाई के प्रतिशत को प्राप्त करता है या सेट करता है जो चित्र के दाएँ तरफ़ से काटा जाता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

वास्तविक छवि की ऊँचाई के प्रतिशत को प्राप्त करता है या सेट करता है जो चित्र के नीचे से काटा जाता है। पढ़ने/लिखने योग्य float।

**वापसी:**  
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

वास्तविक छवि की ऊँचाई के प्रतिशत को प्राप्त करता है या सेट करता है जो चित्र के नीचे से काटा जाता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

भराव चित्र के कटे हुए क्षेत्रों को हटाता है।

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // PictureFrame प्राप्त करता है
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // PictureFrame छवि के कटे हुए क्षेत्रों को हटाता है
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**वापसी:**  
[IPPImage](../../com.aspose.slides/ippimage) - यदि कटाई आवश्यक नहीं है तो मूल छवि, अन्यथा कटाई की गई छवि।

--------------------

यह मेथड WMF/EMF मेटा-फ़ाइलों को रास्टर PNG छवि में परिवर्तित करता है जबकि कटाई करता है।

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

आकार और निर्दिष्ट रिज़ॉल्यूशन के आधार पर छवि का आकार कम करके उसे संकुचित करता है। वैकल्पिक रूप से, यह कटे हुए क्षेत्रों को भी हटाता है।

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` मेथड प्रस्तुति में छवि का आकार कम करने के लिए लक्ष्य रिज़ॉल्यूशन सेट करके और कटे हुए क्षेत्रों को हटाकर उपयोग किया जाता है:
>   
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // लक्ष्य रिज़ॉल्यूशन 150 DPI (वेब रिज़ॉल्यूशन) के साथ छवि को संकुचित करें और कटे हुए क्षेत्रों को हटाएँ
>      boolean result = picFrame.getPictureFormat().compressImage(true, PicturesCompression.Dpi150);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | यदि true, तो मेथड छवि के कटे हुए क्षेत्रों को हटा देगा, जिससे आकार और अधिक घट सकता है। |
| resolution | int | संपीड़न के लिए लक्ष्य रिज़ॉल्यूशन, जिसे [PicturesCompression](../../com.aspose.slides/picturescompression) enum के मान के रूप में बताया गया है। |

--------------------

यह मेथड चित्र के आकार और रिज़ॉल्यूशन को बदलता है, जो PowerPoint के "Picture Format -> Compress Pictures" फीचर के समान है। |

**वापसी:**
boolean - यह बूलियन दर्शाता है कि छवि सफलतापूर्वक संकुचित हुई या नहीं। यदि छवि को पुनः आकार दिया गया या काटा गया तो true लौटाता है, अन्यथा false।

### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> नीचे दिया गया उदाहरण दर्शाता है कि कैसे ```
> CompressImage
> ```
 मेथड का उपयोग करके प्रस्तुति में छवि का आकार लक्ष्य रिज़ॉल्यूशन सेट करके और कटे हुए क्षेत्रों को हटाकर कम किया जाता है:
>   
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // PictureFrame प्राप्त करें
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // लक्ष्य रिज़ॉल्यूशन 150 DPI (वेब रिज़ॉल्यूशन) के साथ छवि को संकुचित करें और कटे हुए क्षेत्रों को हटाएँ
>      boolean result = picFrame.getPictureFormat().compressImage(true, 150f); // Web resolution
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | यदि true हो, तो मेथड छवि के कटे हुए क्षेत्रों को हटा देगा, जिससे आकार और अधिक घट सकता है। |
| resolution | float | लक्ष्य रिज़ॉल्यूशन DPI में। यह मान सकारात्मक होना चाहिए और यह निर्धारित करता है कि छवि कैसे पुनः आकार दी जाएगी।

--------------------

यह मेथड चित्र के आकार और रिज़ॉल्यूशन को बदलता है, जो PowerPoint के "Picture Format -> Compress Pictures" फीचर के समान है। |

**वापसी:**
boolean - एक boolean जो दर्शाता है कि छवि सफलतापूर्वक संकुचित हुई या नहीं। यदि छवि को पुनः आकार दिया गया या काटा गया तो true लौटाता है, अन्यथा false।
### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public final float getStretchOffsetLeft()
```

भराव आयत के बाएँ किनारे को प्राप्त करता है या सेट करता है जो आकार की बाउंडिंग बॉक्स के बाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित है। सकारात्मक प्रतिशत एक इंट्रेस्ट (अंदर की ओर) दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट (बाहर की ओर) दर्शाता है। पढ़ने/लिखने योग्य float .

**वापसी:**
float
### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public final void setStretchOffsetLeft(float value)
```

भराव आयत के बाएँ किनारे को प्राप्त करता है या सेट करता है जो आकार की बाउंडिंग बॉक्स के बाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित है। सकारात्मक प्रतिशत एक इंट्रेस्ट दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट दर्शाता है। पढ़ने/लिखने योग्य float .

**Returns:**
float
### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public final float getStretchOffsetTop()
```

Returns or sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public final void setStretchOffsetTop(float value)
```

Returns or sets top edge of the fill rectangle that is defined by a percentage offset from the top edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public final float getStretchOffsetRight()
```

Returns or sets right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public final void setStretchOffsetRight(float value)
```

Returns or sets right edge of the fill rectangle that is defined by a percentage offset from the right edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public final float getStretchOffsetBottom()
```

भराव आयत के नीचे किनारे को प्राप्त करता है या सेट करता है जो आकार की बाउंडिंग बॉक्स के नीचे किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित है। एक सकारात्मक प्रतिशत इंट्रेस्ट दर्शाता है, जबकि एक नकारात्मक प्रतिशत आउटसेट दर्शाता है। पढ़ने/लिखने योग्य float .

**वापसी:**
float
### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public final void setStretchOffsetBottom(float value)
```

भराव आयत के नीचे किनारे को प्राप्त करता है या सेट करता है जो आकार की बाउंडिंग बॉक्स के नीचे किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित है। एक सकारात्मक प्रतिशत इंट्रेस्ट दर्शाता है, जबकि एक नकारात्मक प्रतिशत आउटसेट दर्शाता है। पढ़ने/लिखने योग्य float .

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getTileOffsetX() {#getTileOffsetX--}
```
public final float getTileOffsetX()
```


Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // आकार के picture fill format प्राप्त करें
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // picture fill mode को Tile सेट करें
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // टेक्सचर का क्षैतिज ऑफ़सेट 20 पॉइंट सेट करें
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileOffsetX(float value) {#setTileOffsetX-float-}
```
public final void setTileOffsetX(float value)
```


Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // आकार के picture fill format प्राप्त करें
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // picture fill mode को Tile सेट करें
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // टेक्सचर का क्षैतिज ऑफ़सेट 20 पॉइंट सेट करें
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getTileOffsetY() {#getTileOffsetY--}
```
public final float getTileOffsetY()
```


Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // आकार के picture fill format प्राप्त करें
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // picture fill mode को Tile सेट करें
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // टेक्सचर का लंबवत ऑफ़सेट -50 पॉइंट सेट करें
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileOffsetY(float value) {#setTileOffsetY-float-}
```
public final void setTileOffsetY(float value)
```


Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // आकार के picture fill format प्राप्त करें
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // picture fill mode को Tile सेट करें
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // टेक्सचर का लंबवत ऑफ़सेट -50 पॉइंट सेट करें
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileScaleX() {#getTileScaleX--}
```
public final float getTileScaleX()
```


Returns or sets the horizontal scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // आकार के picture fill format प्राप्त करें
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // picture fill mode को Tile सेट करें
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // टेक्सचर का क्षैतिज स्केल 120 प्रतिशत सेट करें
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Returns:**
float
### setTileScaleX(float value) {#setTileScaleX-float-}
```
public final void setTileScaleX(float value)
```


Returns or sets the horizontal scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // आकार के picture fill format प्राप्त करें
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // picture fill mode को Tile सेट करें
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // टेक्सचर का क्षैतिज स्केल 120 प्रतिशत सेट करें
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileScaleY() {#getTileScaleY--}
```
public final float getTileScaleY()
```


Returns or sets the vertical scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // आकार के picture fill format प्राप्त करें
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // picture fill mode को Tile सेट करें
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // टेक्सचर का लंबवत स्केल 120 प्रतिशत सेट करें
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Returns:**
float
### setTileScaleY(float value) {#setTileScaleY-float-}
```
public final void setTileScaleY(float value)
```


Returns or sets the vertical scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // आकार के picture fill format प्राप्त करें
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // picture fill mode को Tile सेट करें
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // टेक्सचर का लंबवत स्केल 120 प्रतिशत सेट करें
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTileAlignment() {#getTileAlignment--}
```
public final byte getTileAlignment()
```


Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // आकार के picture fill format प्राप्त करें
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // picture fill mode को Tile सेट करें
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // टाइल संरेखण को दाएँ-निचले कोने पर सेट करें
>      pictureFillFormat.setTileAlignment(RectangleAlignment.BottomRight);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
 
--------------------

Default is [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Returns:**
byte
### setTileAlignment(byte value) {#setTileAlignment-byte-}
```
public final void setTileAlignment(byte value)
```


Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // आकार के picture fill format प्राप्त करें
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // picture fill mode को Tile सेट करें
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // टाइल संरेखण को दाएँ-निचले कोने पर सेट करें
>      pictureFillFormat.setTileAlignment(RectangleAlignment.BottomRight);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

Default is [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTileFlip() {#getTileFlip--}
```
public final int getTileFlip()
```


Flips the texture tile around its horizontal, vertical or both axis. Read/write [TileFlip](../../com.aspose.slides/tileflip).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // आकार के picture fill format प्राप्त करें
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // picture fill mode को Tile सेट करें
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // टेक्सचर टाइल को उसकी लंबवत धुरी के चारों ओर उलटें।
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
--------------------

Default is [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**Returns:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public final void setTileFlip(int value)
```


Flips the texture tile around its horizontal, vertical or both axis. Read/write [TileFlip](../../com.aspose.slides/tileflip).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // आकार के picture fill format प्राप्त करें
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // picture fill mode को Tile सेट करें
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // टेक्सचर टाइल को उसकी लंबवत धुरी के चारों ओर उलटें।
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

डिफ़ॉल्ट है [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |