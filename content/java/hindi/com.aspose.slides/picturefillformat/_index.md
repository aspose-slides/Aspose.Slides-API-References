---
title: PictureFillFormat
second_title: Aspose.Slides for Java API संदर्भ
description: एक चित्र भराव शैली का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/picturefillformat/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)  
```
public final class PictureFillFormat extends PVIObject implements IPictureFillFormat
```

एक चित्र फ़िल शैली का प्रतिनिधित्व करता है।  
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDpi()](#getDpi--) | पिक्चर को भरने के लिए उपयोग किए जाने वाले DPI को प्राप्त करता है या सेट करता है। |
| [setDpi(int value)](#setDpi-int-) | पिक्चर को भरने के लिए उपयोग किए जाने वाले DPI को प्राप्त करता है या सेट करता है। |
| [getPictureFillMode()](#getPictureFillMode--) | पिक्चर भरने के मोड को प्राप्त करता है या सेट करता है। |
| [setPictureFillMode(int value)](#setPictureFillMode-int-) | पिक्चर भरने के मोड को प्राप्त करता है या सेट करता है। |
| [getPicture()](#getPicture--) | पिक्चर को प्राप्त करता है। |
| [getCropLeft()](#getCropLeft--) | पिक्चर के बाएँ हिस्से से काटे गए वास्तविक चित्र की चौड़ाई के प्रतिशत संख्या को प्राप्त करता है या सेट करता है। |
| [setCropLeft(float value)](#setCropLeft-float-) | पिक्चर के बाएँ हिस्से से काटे गए वास्तविक चित्र की चौड़ाई के प्रतिशत संख्या को प्राप्त करता है या सेट करता है। |
| [getCropTop()](#getCropTop--) | पिक्चर के शीर्ष से काटी गई वास्तविक चित्र की ऊँचाई के प्रतिशत संख्या को प्राप्त करता है या सेट करता है। |
| [setCropTop(float value)](#setCropTop-float-) | पिक्चर के शीर्ष से काटी गई वास्तविक चित्र की ऊँचाई के प्रतिशत संख्या को प्राप्त करता है या सेट करता है। |
| [getCropRight()](#getCropRight--) | पिक्चर के दाएँ हिस्से से काटे गए वास्तविक चित्र की चौड़ाई के प्रतिशत संख्या को प्राप्त करता है या सेट करता है। |
| [setCropRight(float value)](#setCropRight-float-) | पिक्चर के दाएँ हिस्से से काटे गए वास्तविक चित्र की चौड़ाई के प्रतिशत संख्या को प्राप्त करता है या सेट करता है। |
| [getCropBottom()](#getCropBottom--) | पिक्चर के नीचे से काटी गई वास्तविक चित्र की ऊँचाई के प्रतिशत संख्या को प्राप्त करता है या सेट करता है। |
| [setCropBottom(float value)](#setCropBottom-float-) | पिक्चर के नीचे से काटी गई वास्तविक चित्र की ऊँचाई के प्रतिशत संख्या को प्राप्त करता है या सेट करता है। |
| [deletePictureCroppedAreas()](#deletePictureCroppedAreas--) | भरे हुए पिक्चर के काटे गये क्षेत्रों को हटाएँ। |
| [compressImage(boolean deleteCroppedAreasOfImage, int resolution)](#compressImage-boolean-int-) | आकार के आकार और निर्दिष्ट रिज़ॉल्यूशन के आधार पर आकार घटाकर छवि को संकुचित करता है। |
| [compressImage(boolean deleteCroppedAreasOfImage, float resolution)](#compressImage-boolean-float-) | आकार के आकार और निर्दिष्ट रिज़ॉल्यूशन के आधार पर आकार घटाकर छवि को संकुचित करता है। |
| [getStretchOffsetLeft()](#getStretchOffsetLeft--) | शेप के बाउंडिंग बॉक्स के बाएँ किनारे से प्रतिशत ऑफसेट द्वारा परिभाषित भराव आयत के बाएँ किनारे को प्राप्त करता है या सेट करता है। |
| [setStretchOffsetLeft(float value)](#setStretchOffsetLeft-float-) | शेप के बाउंडिंग बॉक्स के बाएँ किनारे से प्रतिशत ऑफसेट द्वारा परिभाषित भराव आयत के बाएँ किनारे को प्राप्त करता है या सेट करता है। |
| [getStretchOffsetTop()](#getStretchOffsetTop--) | शेप के बाउंडिंग बॉक्स के शीर्ष किनारे से प्रतिशत ऑफसेट द्वारा परिभाषित भराव आयत के शीर्ष किनारे को प्राप्त करता है या सेट करता है। |
| [setStretchOffsetTop(float value)](#setStretchOffsetTop-float-) | शेप के बाउंडिंग बॉक्स के शीर्ष किनारे से प्रतिशत ऑफसेट द्वारा परिभाषित भराव आयत के शीर्ष किनारे को प्राप्त करता है या सेट करता है। |
| [getStretchOffsetRight()](#getStretchOffsetRight--) | शेप के बाउंडिंग बॉक्स के दाएँ किनारे से प्रतिशत ऑफसेट द्वारा परिभाषित भराव आयत के दाएँ किनारे को प्राप्त करता है या सेट करता है। |
| [setStretchOffsetRight(float value)](#setStretchOffsetRight-float-) | शेप के बाउंडिंग बॉक्स के दाएँ किनारे से प्रतिशत ऑफसेट द्वारा परिभाषित भराव आयत के दाएँ किनारे को प्राप्त करता है या सेट करता है। |
| [getStretchOffsetBottom()](#getStretchOffsetBottom--) | शेप के बाउंडिंग बॉक्स के नीचे किनारे से प्रतिशत ऑफसेट द्वारा परिभाषित भराव आयत के नीचे किनारे को प्राप्त करता है या सेट करता है। |
| [setStretchOffsetBottom(float value)](#setStretchOffsetBottom-float-) | शेप के बाउंडिंग बॉक्स के नीचे किनारे से प्रतिशत ऑफसेट द्वारा परिभाषित भराव आयत के नीचे किनारे को प्राप्त करता है या सेट करता है। |
| [getTileOffsetX()](#getTileOffsetX--) | शेप की मूल स्थिति से बिंदुओं में टेक्सचर के क्षैतिज ऑफसेट को प्राप्त करता है या सेट करता है। |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | शेप की मूल स्थिति से बिंदुओं में टेक्सचर के क्षैतिज ऑफसेट को प्राप्त करता है या सेट करता है। |
| [getTileOffsetY()](#getTileOffsetY--) | शेप की मूल स्थिति से बिंदुओं में टेक्सचर के ऊर्ध्वाधर ऑफसेट को प्राप्त करता है या सेट करता है। |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | शेप की मूल स्थिति से बिंदुओं में टेक्सचर के ऊर्ध्वाधर ऑफसेट को प्राप्त करता है या सेट करता है। |
| [getTileScaleX()](#getTileScaleX--) | टेक्सचर भराव के लिए क्षैतिज स्केल को प्रतिशत के रूप में प्राप्त करता है या सेट करता है। |
| [setTileScaleX(float value)](#setTileScaleX-float-) | टेक्सचर भराव के लिए क्षैतिज स्केल को प्रतिशत के रूप में प्राप्त करता है या सेट करता है। |
| [getTileScaleY()](#getTileScaleY--) | टेक्सचर भराव के लिए ऊर्ध्वाधर स्केल को प्रतिशत के रूप में प्राप्त करता है या सेट करता है। |
| [setTileScaleY(float value)](#setTileScaleY-float-) | टेक्सचर भराव के लिए ऊर्ध्वाधर स्केल को प्रतिशत के रूप में प्राप्त करता है या सेट करता है। |
| [getTileAlignment()](#getTileAlignment--) | शेप के भीतर टेक्सचर कैसे संरेखित है, इसे प्राप्त करता है या सेट करता है। |
| [setTileAlignment(byte value)](#setTileAlignment-byte-) | शेप के भीतर टेक्सचर कैसे संरेखित है, इसे प्राप्त करता है या सेट करता है। |
| [getTileFlip()](#getTileFlip--) | टेक्सचर टाइल को उसके क्षैतिज, ऊर्ध्वाधर या दोनों अक्षों के चारों ओर फ़्लिप करता है। |
| [setTileFlip(int value)](#setTileFlip-int-) | टेक्सचर टाइल को उसके क्षैतिज, ऊर्ध्वाधर या दोनों अक्षों के चारों ओर फ़्लिप करता है। |

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने-योग्य long.

**रिटर्न:**  
long

### getDpi() {#getDpi--}
```
public final int getDpi()
```

पिक्चर को भरने के लिए उपयोग किए जाने वाले DPI को प्राप्त करता है या सेट करता है। पढ़ने-लिखने-योग्य int ।

**रिटर्न:**  
int

### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```

पिक्चर को भरने के लिए उपयोग किए जाने वाले DPI को प्राप्त करता है या सेट करता है। पढ़ने-लिखने-योग्य int ।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPictureFillMode() {#getPictureFillMode--}
```
public final int getPictureFillMode()
```

पिक्चर भरने के मोड को प्राप्त करता है या सेट करता है। पढ़ने-लिखने-योग्य [PictureFillMode](../../com.aspose.slides/picturefillmode)।

**रिटर्न:**  
int

### setPictureFillMode(int value) {#setPictureFillMode-int-}
```
public final void setPictureFillMode(int value)
```

पिक्चर भरने के मोड को प्राप्त करता है या सेट करता है। पढ़ने-लिखने-योग्य [PictureFillMode](../../com.aspose.slides/picturefillmode)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

पिक्चर को प्राप्त करता है। केवल-पढ़ने-योग्य [ISlidesPicture](../../com.aspose.slides/islidespicture)।

**रिटर्न:**  
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getCropLeft() {#getCropLeft--}
```
public final float getCropLeft()
```

पिक्चर के बाएँ हिस्से से काटे गए वास्तविक चित्र की चौड़ाई के प्रतिशत संख्या को प्राप्त करता है या सेट करता है। पढ़ने-लिखने-योग्य float ।

**रिटर्न:**  
float

### setCropLeft(float value) {#setCropLeft-float-}
```
public final void setCropLeft(float value)
```

पिक्चर के बाएँ हिस्से से काटे गए वास्तविक चित्र की चौड़ाई के प्रतिशत संख्या को प्राप्त करता है या सेट करता है। पढ़ने-लिखने-योग्य float ।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getCropTop() {#getCropTop--}
```
public final float getCropTop()
```

पिक्चर के शीर्ष से काटी गई वास्तविक चित्र की ऊँचाई के प्रतिशत संख्या को प्राप्त करता है या सेट करता है। पढ़ने-लिखने-योग्य float ।

**रिटर्न:**  
float

### setCropTop(float value) {#setCropTop-float-}
```
public final void setCropTop(float value)
```

पिक्चर के शीर्ष से काटी गई वास्तविक चित्र की ऊँचाई के प्रतिशत संख्या को प्राप्त करता है या सेट करता है। पढ़ने-लिखने-योग्य float ।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getCropRight() {#getCropRight--}
```
public final float getCropRight()
```

पिक्चर के दाएँ हिस्से से काटे गए वास्तविक चित्र की चौड़ाई के प्रतिशत संख्या को प्राप्त करता है या सेट करता है। पढ़ने-लिखने-योग्य float ।

**रिटर्न:**  
float

### setCropRight(float value) {#setCropRight-float-}
```
public final void setCropRight(float value)
```

पिक्चर के दाएँ हिस्से से काटे गए वास्तविक चित्र की चौड़ाई के प्रतिशत संख्या को प्राप्त करता है या सेट करता है। पढ़ने-लिखने-योग्य float ।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getCropBottom() {#getCropBottom--}
```
public final float getCropBottom()
```

पिक्चर के नीचे से काटी गई वास्तविक चित्र की ऊँचाई के प्रतिशत संख्या को प्राप्त करता है या सेट करता है। पढ़ने-लिखने-योग्य float ।

**रिटर्न:**  
float

### setCropBottom(float value) {#setCropBottom-float-}
```
public final void setCropBottom(float value)
```

पिक्चर के नीचे से काटी गई वास्तविक चित्र की ऊँचाई के प्रतिशत संख्या को प्राप्त करता है या सेट करता है। पढ़ने-लिखने-योग्य float ।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### deletePictureCroppedAreas() {#deletePictureCroppedAreas--}
```
public final IPPImage deletePictureCroppedAreas()
```

भरे हुए पिक्चर के काटे गये क्षेत्रों को हटाएँ।

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


**रिटर्न:**  
[IPPImage](../../com.aspose.slides/ippimage) - कटा हुआ छवि या मूल छवि यदि क्रॉपिंग आवश्यक नहीं है।

--------------------

यह विधि WMF/EMF मेटाफाइलों को रास्टर PNG छवि में बदलती है जबकि क्रॉपिंग करती है।

### compressImage(boolean deleteCroppedAreasOfImage, int resolution) {#compressImage-boolean-int-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, int resolution)
```

शेप के आकार और निर्दिष्ट रिज़ॉल्यूशन के आधार पर आकार घटाकर छवि को संकुचित करता है। वैकल्पिक रूप से, यह भी कटे हुए क्षेत्रों को हटाता है।

--------------------

> ```
> The following example demonstrates how to use the ```
> CompressImage
> ``` विधि एक प्रस्तुति में छवि के आकार को लक्ष्य रिज़ॉल्यूशन सेट करके और कटे हुए क्षेत्रों को हटाकर घटाने के लिए:  
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
boolean - A boolean indicating whether the image was successfully compressed. Returns   if the image was resized or cropped, otherwise  .
### compressImage(boolean deleteCroppedAreasOfImage, float resolution) {#compressImage-boolean-float-}
```
public final boolean compressImage(boolean deleteCroppedAreasOfImage, float resolution)
```


Compresses the image by reducing its size based on the shape size and specified resolution. Optionally, it also deletes cropped areas.

--------------------

> ```
> निम्नलिखित उदाहरण दिखाता है कि कैसे ```
> CompressImage
> ```
 विधि का उपयोग करके एक प्रस्तुति में छवि के आकार को लक्ष्य रिज़ॉल्यूशन सेट करके और कटे हुए क्षेत्रों को हटाकर घटाया जा सकता है:  
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
boolean - A  boolean  indicating whether the image was successfully compressed. Returns   if the image was resized or cropped, otherwise  .
### getStretchOffsetLeft() {#getStretchOffsetLeft--}
```
public final float getStretchOffsetLeft()
```

Returns or sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetLeft(float value) {#setStretchOffsetLeft-float-}
```
public final void setStretchOffsetLeft(float value)
```

Returns or sets left edge of the fill rectangle that is defined by a percentage offset from the left edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStretchOffsetTop() {#getStretchOffsetTop--}
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

Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Returns:**
float
### setStretchOffsetBottom(float value) {#setStretchOffsetBottom-float-}
```
public final void setStretchOffsetBottom(float value)
```

Returns or sets bottom edge of the fill rectangle that is defined by a percentage offset from the bottom edge of the shape's bounding box. A positive percentage specifies an inset, while a negative percentage specifies an outset. Read/write  float .

**Parameters:**
| Parameter | Type | Description |
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
public final void setTileOffsetX(float value)
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

**Parameters:**
| Parameter | Type | Description |
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
public final void setTileOffsetY(float value)
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
public final float getTileScaleX()
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
public final void setTileScaleX(float value)
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
public final float getTileScaleY()
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
public final void setTileScaleY(float value)
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
>  } while {  
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

**Returns:**
byte
### setTileAlignment(byte value) {#setTileAlignment-byte-}
```
public final void setTileAlignment(byte value)
```
--------------------

Default is [RectangleAlignment.TopLeft](../../com.aspose.slides/rectanglealignment\#TopLeft).

**Returns:**
byte
### setTileAlignment(byte value) {#setTileAlignment-byte-}
```
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
public final int getTileFlip()
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
public final void setTileFlip(int value)
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

डिफ़ॉल्ट है [TileFlip.NoFlip](../../com.aspose.slides/tileflip\#NoFlip)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |