---
title: ISVGOptions
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एक SVG विकल्प का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/isvgoptions/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

एक SVG विकल्प को दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | यह निर्धारित करता है कि स्लाइड पर पाठ को ग्राफ़िक्स के रूप में सहेजा जाएगा या नहीं। |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | यह निर्धारित करता है कि स्लाइड पर पाठ को ग्राफ़िक्स के रूप में सहेजा जाएगा या नहीं। |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | मेटा-फ़ाइल रास्टराइज़ेशन के लिए निचली रिज़ॉल्यूशन सीमा को लौटाता या सेट करता है। |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | मेटा-फ़ाइल रास्टराइज़ेशन के लिए निचली रिज़ॉल्यूशन सीमा को लौटाता या सेट करता है। |
| [getDisable3DText()](#getDisable3DText--) | यह निर्धारित करता है कि SVG में 3D पाठ निष्क्रिय है या नहीं। |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | यह निर्धारित करता है कि SVG में 3D पाठ निष्क्रिय है या नहीं। |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | FromCornerX और FromCenter ग्रेडिएंट के विभाजन को निष्क्रिय करता है। |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | FromCornerX और FromCenter ग्रेडिएंट के विभाजन को निष्क्रिय करता है। |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 में मार्करों के लिए इनसेट निर्धारित करने की क्षमता नहीं है। |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 में मार्करों के लिए इनसेट निर्धारित करने की क्षमता नहीं है। |
| [getJpegQuality()](#getJpegQuality--) | JPEG एन्कोडिंग गुणवत्ता निर्धारित करता है। |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG एन्कोडिंग गुणवत्ता निर्धारित करता है। |
| [getShapeFormattingController()](#getShapeFormattingController--) | ऐसे कॉलबैक इंटरफ़ेस को लौटाता और सेट करता है जो उपयोगकर्ता को शेप रूपांतरण नियंत्रित करने की अनुमति देता है। |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | ऐसे कॉलबैक इंटरफ़ेस को लौटाता और सेट करता है जो उपयोगकर्ता को शेप रूपांतरण नियंत्रित करने की अनुमति देता है। |
| [getPicturesCompression()](#getPicturesCompression--) | चित्र संपीड़न स्तर को दर्शाता है पढ़ने/लेखन #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | चित्र संपीड़न स्तर को दर्शाता है पढ़ने/लेखन #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | एक बूलियन फ़्लैग इंगित करता है कि क्रॉप किए गए भाग दस्तावेज़ का हिस्सा बने रहते हैं या नहीं। |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | एक बूलियन फ़्लैग इंगित करता है कि क्रॉप किए गए भाग दस्तावेज़ का हिस्सा बने रहते हैं या नहीं। |
| [getUseFrameSize()](#getUseFrameSize--) | यह निर्धारित करता है कि टेक्स्ट फ्रेम रेंडरिंग क्षेत्र में शामिल होगा या नहीं। |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | यह निर्धारित करता है कि टेक्स्ट फ्रेम रेंडरिंग क्षेत्र में शामिल होगा या नहीं। |
| [getUseFrameRotation()](#getUseFrameRotation--) | रेंडरिंग के दौरान शेप के निर्दिष्ट घूर्णन को लागू करना है या नहीं, यह निर्धारित करता है। |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | रेंडरिंग के दौरान शेप के निर्दिष्ट घूर्णन को लागू करना है या नहीं, यह निर्धारित करता है। |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | बाहरी लोड किए गए फ़ॉन्ट को संभालने का तरीका निर्धारित करता है। |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | बाहरी लोड किए गए फ़ॉन्ट को संभालने का तरीका निर्धारित करता है। |
| [getInkOptions()](#getInkOptions--) | निर्यात किए गए दस्तावेज़ में Ink वस्तुओं की दिखावट को नियंत्रित करने के विकल्प प्रदान करता है। |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | यह दर्शाने वाला मान प्राप्त करता या सेट करता है कि पाठ को लिगेचर के बिना रेंडर किया गया है या नहीं। |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | यह दर्शाने वाला मान प्राप्त करता या सेट करता है कि पाठ को लिगेचर के बिना रेंडर किया गया है या नहीं। |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

यह निर्धारित करता है कि स्लाइड पर पाठ को ग्राफ़िक्स के रूप में सहेजा जाएगा या नहीं। पढ़ने/लेखन बूलियन।

**वापसी:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

यह निर्धारित करता है कि स्लाइड पर पाठ को ग्राफ़िक्स के रूप में सहेजा जाएगा या नहीं। पढ़ने/लेखन बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

मेटा-फ़ाइल रास्टराइज़ेशन के लिए निचली रिज़ॉल्यूशन सीमा को लौटाता या सेट करता है। पढ़ने/लेखन int।

**वापसी:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

मेटा-फ़ाइल रास्टराइज़ेशन के लिए निचली रिज़ॉल्यूशन सीमा को लौटाता या सेट करता है। पढ़ने/लेखन int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

यह निर्धारित करता है कि SVG में 3D पाठ निष्क्रिय है या नहीं। पढ़ने/लेखन बूलियन।

**वापसी:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

यह निर्धारित करता है कि SVG में 3D पाठ निष्क्रिय है या नहीं। पढ़ने/लेखन बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

FromCornerX और FromCenter ग्रेडिएंट के विभाजन को निष्क्रिय करता है। पढ़ने/लेखन बूलियन।

**वापसी:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

FromCornerX और FromCenter ग्रेडिएंट के विभाजन को निष्क्रिय करता है। पढ़ने/लेखन बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 में मार्करों के लिए इनसेट निर्धारित करने की क्षमता नहीं है। Aspose.Slides SVG लेखन इंजन इस समस्या के लिए एक वैकल्पिक तरीका प्रदान करता है: यह तीर वाले रेखा के अंत को क्रॉप करता है, जिससे रेखा मार्करों को ओवरलैप नहीं करती। यह विकल्प इस व्यवहार को बंद करता है। पढ़ने/लेखन बूलियन।

**वापसी:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 में मार्करों के लिए इनसेट निर्धारित करने की क्षमता नहीं है। Aspose.Slides SVG लेखन इंजन इस समस्या के लिए एक वैकल्पिक तरीका प्रदान करता है: यह तीर वाले रेखा के अंत को क्रॉप करता है, जिससे रेखा मार्करों को ओवरलैप नहीं करती। यह विकल्प इस व्यवहार को बंद करता है। पढ़ने/लेखन बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

JPEG एन्कोडिंग गुणवत्ता निर्धारित करता है। पढ़ने/लेखन int।

**वापसी:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

JPEG एन्कोडिंग गुणवत्ता निर्धारित करता है। पढ़ने/लेखन int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

शेप रूपांतरण को नियंत्रित करने हेतु उपयोगकर्ता को अनुमति देने वाला कॉलबैक इंटरफ़ेस लौटाता और सेट करता है। पढ़ने/लेखन [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)।

**वापसी:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

शेप रूपांतरण को नियंत्रित करने हेतु उपयोगकर्ता को अनुमति देने वाला कॉलबैक इंटरफ़ेस लौटाता और सेट करता है। पढ़ने/लेखन [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

चित्र संपीड़न स्तर को दर्शाता है पढ़ने/लेखन #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int).

**वापसी:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

चित्र संपीड़न स्तर को दर्शाता है पढ़ने/लेखन #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

एक बूलियन फ़्लैग इंगित करता है कि क्रॉप किए गए भाग दस्तावेज़ का हिस्सा बने रहते हैं या नहीं। यदि true है तो क्रॉप किए गए भाग हटा दिए जाएंगे, यदि false है तो वे दस्तावेज़ में क्रमबद्ध रहेंगे (जिससे फ़ाइल आकार बड़ा हो सकता है) पढ़ने/लेखन बूलियन।

**वापसी:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

एक बूलियन फ़्लैग इंगित करता है कि क्रॉप किए गए भाग दस्तावेज़ का हिस्सा बने रहते हैं या नहीं। यदि true है तो क्रॉप किए गए भाग हटा दिए जाएंगे, यदि false है तो वे दस्तावेज़ में क्रमबद्ध रहेंगे (जिससे फ़ाइल आकार बड़ा हो सकता है) पढ़ने/लेखन बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

यह निर्धारित करता है कि टेक्स्ट फ्रेम रेंडरिंग क्षेत्र में शामिल होगा या नहीं। पढ़ने/लेखन बूलियन। डिफ़ॉल्ट मान false है।

**वापसी:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

यह निर्धारित करता है कि टेक्स्ट फ्रेम रेंडरिंग क्षेत्र में शामिल होगा या नहीं। पढ़ने/लेखन बूलियन। डिफ़ॉल्ट मान false है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

रेंडरिंग के दौरान शेप के निर्दिष्ट घूर्णन को लागू करना है या नहीं, यह निर्धारित करता है। पढ़ने/लेखन बूलियन। डिफ़ॉल्ट मान true है।

**वापसी:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

रेंडरिंग के दौरान शेप के निर्दिष्ट घूर्णन को लागू करना है या नहीं, यह निर्धारित करता है। पढ़ने/लेखन बूलियन। डिफ़ॉल्ट मान true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

बाहरी लोड किए गए फ़ॉन्ट को संभालने का तरीका निर्धारित करता है। पढ़ने/लेखन [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling)।

**वापसी:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

बाहरी लोड किए गए फ़ॉन्ट को संभालने का तरीका निर्धारित करता है। पढ़ने/लेखन [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

निर्यात किए गए दस्तावेज़ में Ink वस्तुओं की दिखावट को नियंत्रित करने के विकल्प प्रदान करता है। केवल पढ़ने योग्य [IInkOptions](../../com.aspose.slides/iinkoptions)

**वापसी:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

यह दर्शाने वाला मान प्राप्त करता या सेट करता है कि पाठ को लिगेचर के बिना रेंडर किया गया है या नहीं। यदि true सेट किया गया, तो रेंडर किए गए आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से यह मान false है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

यह दर्शाने वाला मान प्राप्त करता या सेट करता है कि पाठ को लिगेचर के बिना रेंडर किया गया है या नहीं। यदि true सेट किया गया, तो रेंडर किए गए आउटपुट में लिगेचर निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से यह मान false है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |