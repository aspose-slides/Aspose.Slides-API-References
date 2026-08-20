---
title: IPictureFillFormat
second_title: Aspose.Slides का Java API संदर्भ
description: एक चित्र भराव शैली का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ipicturefillformat/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormat extends IFillParamSource
```

एक चित्र भराव शैली का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getDpi()](#getDpi--) | चित्र को भरने के लिए उपयोग किए जाने वाले dpi को वापस देता है या सेट करता है। |
| [setDpi(int value)](#setDpi-int-) | चित्र को भरने के लिए उपयोग किए जाने वाले dpi को वापस देता है या सेट करता है। |
| [getPictureFillMode()](#getPictureFillMode--) | चित्र भराव मोड को वापस देता है या सेट करता है। |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | चित्र भराव मोड को वापस देता है या सेट करता है। |
| [getPicture()](#getPicture--) | चित्र को वापस देता है। |
| [getCropLeft()](#getCropLeft--) | बाएँ तरफ़ से काटे गए वास्तविक छवि चौड़ाई के प्रतिशत को वापस देता है या सेट करता है। |
| [setCropLeft(float value)](#setCropLeft-float-) | बाएँ तरफ़ से काटे गए वास्तविक छवि चौड़ाई के प्रतिशत को वापस देता है या सेट करता है। |
| [getCropTop()](#getCropTop--) | ऊपर से काटे गए वास्तविक छवि ऊँचाई के प्रतिशत को वापस देता है या सेट करता है। |
| [setCropTop(float value)](#setCropTop-float-) | ऊपर से काटे गए वास्तविक छवि ऊँचाई के प्रतिशत को वापस देता है या सेट करता है। |
| [getCropRight()](#getCropRight--) | दाएँ तरफ़ से काटे गए वास्तविक छवि चौड़ाई के प्रतिशत को वापस देता है या सेट करता है। |
| [setCropRight(float value)](#setCropRight-float-) | दाएँ तरफ़ से काटे गए वास्तविक छवि चौड़ाई के प्रतिशत को वापस देता है या सेट करता है। |
| [getCropBottom()](#getCropBottom--) | नीचे से काटे गए वास्तविक छवि ऊँचाई के प्रतिशत को वापस देता है या सेट करता है। |
| [setCropBottom(float value)](#setCropBottom-float-) | नीचे से काटे गए वास्तविक छवि ऊँचाई के प्रतिशत को वापस देता है या सेट करता है। |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | आकार की बाउंडिंग बॉक्स के बाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के बाएँ किनारे को वापस देता है या सेट करता है। |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | आकार की बाउंडिंग बॉक्स के बाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के बाएँ किनारे को वापस देता है या सेट करता है। |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | आकार की बाउंडिंग बॉक्स के ऊपर किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के ऊपर किनारे को वापस देता है या सेट करता है। |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | आकार की बाउंडिंग बॉक्स के ऊपर किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के ऊपर किनारे को वापस देता है या सेट करता है। |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | आकार की बाउंडिंग बॉक्स के दाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के दाएँ किनारे को वापस देता है या सेट करता है। |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | आकार की बाउंडिंग बॉक्स के दाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के दाएँ किनारे को वापस देता है या सेट करता है। |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | आकार की बाउंडिंग बॉक्स के नीचे किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के नीचे किनारे को वापस देता है या सेट करता है। |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | आकार की बाउंडिंग बॉक्स के नीचे किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के नीचे किनारे को वापस देता है या सेट करता है। |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | भराव चित्र के क्रॉप किए गए क्षेत्रों को हटाता है। |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | आकार के आकार और निर्दिष्ट रिज़ॉल्यूशन के आधार पर छवि का आकार घटाकर इसे संकुचित करता है। |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | आकार के आकार और निर्दिष्ट रिज़ॉल्यूशन के आधार पर छवि का आकार घटाकर इसे संकुचित करता है। |
| [getTileOffsetX()](#getTileOffsetX--) | बिंदुओं में आकार के मूल से बनावट का क्षैतिज ऑफ़सेट वापस देता है या सेट करता है। |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | बिंदुओं में आकार के मूल से बनावट का क्षैतिज ऑफ़सेट वापस देता है या सेट करता है। |
| [getTileOffsetY()](#getTileOffsetY--) | बिंदुओं में आकार के मूल से बनावट का लंबवत ऑफ़सेट वापस देता है या सेट करता है। |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | बिंदुओं में आकार के मूल से बनावट का लंबवत ऑफ़सेट वापस देता है या सेट करता है। |
| [getTileScaleX()](#getTileScaleX--) | प्रतिशत के रूप में बनावट भराव के लिए क्षैतिज स्केल को वापस देता है या सेट करता है। |
| [setTileScaleX(float value)](#setTileScaleX-float-) | प्रतिशत के रूप में बनावट भराव के लिए क्षैतिज स्केल को वापस देता है या सेट करता है। |
| [getTileScaleY()](#getTileScaleY--) | प्रतिशत के रूप में बनावट भराव के लिए लंबवत स्केल को वापस देता है या सेट करता है। |
| [setTileScaleY(float value)](#setTileScaleY-float-) | प्रतिशत के रूप में बनावट भराव के लिए लंबवत स्केल को वापस देता है या सेट करता है। |
| [getTileAlignment()](#getTileAlignment--) | आकार के भीतर बनावट के संरेखण को वापस देता है या सेट करता है। |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | आकार के भीतर बनावट के संरेखण को वापस देता है या सेट करता है। |
| [getTileFlip()](#getTileFlip--) | बनावट टाइल को उसके क्षैतिज, लंबवत या दोनों अक्षों के आसपास फ़्लिप करता है। |
| [setTileFlip(int value)](#setTileFlip-int-) | बनावट टाइल को उसके क्षैतिज, लंबवत या दोनों अक्षों के आसपास फ़्लिप करता है। |

### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

चित्र को भरने के लिए उपयोग किए जाने वाले dpi को वापस देता है या सेट करता है। पढ़ें/लिखें int.

**रिटर्न:**
int

### setDpi(int value) {#setDpi-int-}
```
public abstract void setDpi(int value)
```

चित्र को भरने के लिए उपयोग किए जाने वाले dpi को वापस देता है या सेट करता है। पढ़ें/लिखें int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

चित्र भराव मोड को वापस देता है या सेट करता है। पढ़ें/लिखें [PictureFillMode](../../com.aspose.slides/picturefillmode).

**रिटर्न:**
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public abstract void setPictureFillMode(int value)
```

चित्र भराव मोड को वापस देता है या सेट करता है। पढ़ें/लिखें [PictureFillMode](../../com.aspose.slides/picturefillmode).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

चित्र को वापस देता है। केवल पढ़ने योग्य [ISlidesPicture](../../com.aspose.slides/islidespicture).

**रिटर्न:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

बाएँ तरफ़ से काटे गए वास्तविक छवि चौड़ाई के प्रतिशत को वापस देता है या सेट करता है। पढ़ें/लिखें float.

**रिटर्न:**
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public abstract void setCropLeft(float value)
```

बाएँ तरफ़ से काटे गए वास्तविक छवि चौड़ाई के प्रतिशत को वापस देता है या सेट करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

ऊपर से काटे गए वास्तविक छवि ऊँचाई के प्रतिशत को वापस देता है या सेट करता है। पढ़ें/लिखें float.

**रिटर्न:**
float

### setCropTop(float value) {#setCropTop-float-}
```
public abstract void setCropTop(float value)
```

ऊपर से काटे गए वास्तविक छवि ऊँचाई के प्रतिशत को वापस देता है या सेट करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

दाएँ तरफ़ से काटे गए वास्तविक छवि चौड़ाई के प्रतिशत को वापस देता है या सेट करता है। पढ़ें/लिखें float.

**रिटर्न:**
float

### setCropRight(float value) {#setCropRight-float-}
```
public abstract void setCropRight(float value)
```

दाएँ तरफ़ से काटे गए वास्तविक छवि चौड़ाई के प्रतिशत को वापस देता है या सेट करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

नीचे से काटे गए वास्तविक छवि ऊँचाई के प्रतिशत को वापस देता है या सेट करता है। पढ़ें/लिखें float.

**रिटर्न:**
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public abstract void setCropBottom(float value)
```

नीचे से काटे गए वास्तविक छवि ऊँचाई के प्रतिशत को वापस देता है या सेट करता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public abstract float getStretchOffsetLeft()
```

आकार की बाउंडिंग बॉक्स के बाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के बाएँ किनारे को वापस देता है या सेट करता है। सकारात्मक प्रतिशत इन्सेट दर्शाता है, जबकि नकारात्मक प्रतिशत आउटसेट। पढ़ें/लिखें float.

**रिटर्न:**
float

### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public abstract void setStretchOffsetLeft(float value)
```

आकार की बाउंडिंग बॉक्स के बाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के बाएँ किनारे को वापस देता है या सेट करता है। सकारात्मक प्रतिशत इन्सेट दर्शाता है, जबकि नकारात्मक प्रतिशत आउटसेट। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
```
public abstract float getStretchOffsetTop()
```

आकार की बाउंडिंग बॉक्स के ऊपर किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के ऊपर किनारे को वापस देता है या सेट करता है। सकारात्मक प्रतिशत इन्सेट दर्शाता है, जबकि नकारात्मक प्रतिशत आउटसेट। पढ़ें/लिखें float.

**रिटर्न:**
float

### setStretchOffsetTop(float value) {#setStretchOffsetTop-float-}
```
public abstract void setStretchOffsetTop(float value)
```

आकार की बाउंडिंग बॉक्स के ऊपर किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के ऊपर किनारे को वापस देता है या सेट करता है। सकारात्मक प्रतिशत इन्सेट दर्शाता है, जबकि नकारात्मक प्रतिशत आउटसेट। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetRight() {#getStretchOffsetRight--}
```
public abstract float getStretchOffsetRight()
```

आकार की बाउंडिंग बॉक्स के दाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के दाएँ किनारे को वापस देता है या सेट करता है। सकारात्मक प्रतिशत इन्सेट दर्शाता है, जबकि नकारात्मक प्रतिशत आउटसेट। पढ़ें/लिखें float.

**रिटर्न:**
float

### setStretchOffsetRight(float value) {#setStretchOffsetRight-float-}
```
public abstract void setStretchOffsetRight(float value)
```

आकार की बाउंडिंग बॉक्स के दाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के दाएँ किनारे को वापस देता है या सेट करता है। सकारात्मक प्रतिशत इन्सेट दर्शाता है, जबकि नकारात्मक प्रतिशत आउटसेट। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetBottom() {#getStretchOffsetBottom--}
```
public abstract float getStretchOffsetBottom()
```

आकार की बाउंडिंग बॉक्स के नीचे किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के नीचे किनारे को वापस देता है या सेट करता है। सकारात्मक प्रतिशत इन्सेट दर्शाता है, जबकि नकारात्मक प्रतिशत आउटसेट। पढ़ें/लिखें float.

**रिटर्न:**
float

### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public abstract void setStretchOffsetBottom(float value)
```

आकार की बाउंडिंग बॉक्स के नीचे किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भराव आयत के नीचे किनारे को वापस देता है या सेट करता है। सकारात्मक प्रतिशत इन्सेट दर्शाता है, जबकि नकारात्मक प्रतिशत आउटसेट। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public abstract IPPImage deletePictureCroppedAreas()
```

भरण चित्र के क्रॉप किए गए क्षेत्रों को हटाता है।

--------------------

> ``` 
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // चित्रफ़्रेम प्राप्त करता है
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // PictureFrame छवि के क्रॉप किए हुए क्षेत्रों को हटाता है
>      IPPImage croppedImage = picFrame.getPictureFormat().deletePictureCroppedAreas();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**रिटर्न:**
[IPPImage](../../com.aspose.slides/ippimage) - क्रॉप किया गया चित्र या मूल चित्र यदि क्रॉपिंग आवश्यक नहीं है।

--------------------

यह मेथड WMF/EMF मेटा फ़ाइलों को क्रॉप करते हुए रास्टर PNG चित्र में बदलता है।

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

आकार के आकार और निर्दिष्ट रिज़ॉल्यूशन के आधार पर छवि का आकार घटाकर इसे संकुचित करता है। वैकल्पिक रूप से, यह क्रॉप किए गए क्षेत्रों को भी हटाता है।

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` प्रस्तुति में छवि का आकार लक्ष्य रिज़ॉल्यूशन सेट करके और क्रॉप किए गए क्षेत्रों को हटाकर घटाने की विधि:
>  
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
>      boolean result = picFrame.getPictureFormat().compressImage(true, PicturesCompression.Dpi150);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | If true, the method will remove the cropped areas of the image, potentially further reducing its size. |
| resolution | int | The target resolution for compression, specified as a value of the [PicturesCompression](../../com.aspose.slides/picturescompression) enum.

--------------------

This method changes the image's size and resolution similar to PowerPoint's "Picture Format -> Compress Pictures" feature. |

**Returns:**
boolean - A boolean indicating whether the image was successfully compressed. Returns true if the image was resized or cropped, otherwise false.
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public abstract boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> निम्नलिखित उदाहरण दर्शाता है कि कैसे ```
> CompressImage
> ```
 मेथड का उपयोग करके प्रस्तुति में छवि का आकार लक्ष्य रिज़ॉल्यूशन सेट करके और क्रॉप किए गए क्षेत्रों को हटाकर घटाया जा सकता है:
>   
>  Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the PictureFrame
>      IPictureFrame picFrame = (IPictureFrame)slide.getShapes().get_Item(0);
>      // Compress the image with a target resolution of 150 DPI (Web resolution) and remove cropped areas
>      boolean result = picFrame.getPictureFormat().compressImage(true, 150f); // Web resolution
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| deleteCroppedAreasOfImage | boolean | If true, the method will remove the cropped areas of the image, potentially further reducing its size. |
| resolution | float | The target resolution in DPI. This value must be positive and defines how the image will be resized.

--------------------

This method changes the image's size and resolution similar to PowerPoint's "Picture Format -> Compress Pictures" feature. |

**Returns:**
boolean - A boolean indicating whether the image was successfully compressed. Returns true if the image was resized or cropped, otherwise false.
### getTileOffsetX() {#getTileOffsetX--}
```
public abstract float getTileOffsetX()
```


Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal offset of the texture to 20 points
>      pictureFillFormat.setTileOffsetX(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileOffsetX(float value) {#setTileOffsetX-float-}
```
public abstract void setTileOffsetX(float value)
```


Returns or sets the horizontal offset of the texture from the shape's origin in points. A positive value moves the texture to the right, while a negative value moves it to the left. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal offset of the texture to 20 points
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
public abstract float getTileOffsetY()
```


Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical offset of the texture to -50 points
>      pictureFillFormat.setTileOffsetY(-50);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
float
### setTileOffsetY(float value) {#setTileOffsetY-float-}
```
public abstract void setTileOffsetY(float value)
```


Returns or sets the vertical offset of the texture from the shape's origin in points. A positive value moves the texture down, while a negative value moves it up. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical offset of the texture to -50 points
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
public abstract float getTileScaleX()
```


Returns or sets the horizontal scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleX(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Returns:**
float
### setTileScaleX(float value) {#setTileScaleX-float-}
```
public abstract void setTileScaleX(float value)
```


Returns or sets the horizontal scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the horizontal scale for the texture to 120 percents
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
public abstract float getTileScaleY()
```


Returns or sets the vertical scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical scale for the texture to 120 percents
>      pictureFillFormat.setTileScaleY(120);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```
**Returns:**
float
### setTileScaleY(float value) {#setTileScaleY-float-}
```
public abstract void setTileScaleY(float value)
```


Returns or sets the vertical scale for the texture fill as a percentage. Read/write  float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the vertical scale for the texture to 120 percents
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
public abstract byte getTileAlignment()
```


Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the alignment for the tiling to the right bottom
>      pictureFillFormat.setTileAlignment(RectangleAlignment.BottomRight);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

डिफ़ॉल्ट है [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Returns:**
byte
### setTileAlignment(byte value) {#setTileAlignment-byte-}
```
public abstract void setTileAlignment(byte value)
```


Returns or sets how the texture is aligned within the shape. This setting controls the starting point of the texture pattern and how it repeats across the shape. Read/write [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Sets the alignment for the tiling to the right bottom
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
public abstract int getTileFlip()
```


Flips the texture tile around its horizontal, vertical or both axis. Read/write [TileFlip](../../com.aspose.slides/tileflip).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Flips the texture tile around its vertical axis.
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
public abstract void setTileFlip(int value)
```


Flips the texture tile around its horizontal, vertical or both axis. Read/write [TileFlip](../../com.aspose.slides/tileflip).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
>      // Gets the picture fill format of the shape
>      IPictureFillFormat pictureFillFormat = slide.getShapes().get_Item(0).getFillFormat().getPictureFillFormat();
>      // Sets the picture fill mode to Tile
>      pictureFillFormat.setPictureFillMode(PictureFillMode.Tile);
>      // Flips the texture tile around its vertical axis.
>      pictureFillFormat.setTileFlip(TileFlip.FlipY);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

डिफ़ॉल्ट है [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |