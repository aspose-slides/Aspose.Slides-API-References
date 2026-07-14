---
title: ISVGOptions
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: SVG विकल्पों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/isvgoptions/
---
**सभी कार्यान्वित इंटरफेस:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

SVG विकल्पों का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | निर्धारित करता है कि स्लाइड पर टेक्स्ट को ग्राफिक्स के रूप में सहेजा जाएगा या नहीं। |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | निर्धारित करता है कि स्लाइड पर टेक्स्ट को ग्राफिक्स के रूप में सहेजा जाएगा या नहीं। |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | मेटाफाइल रास्टराइजेशन के लिए निचली रिज़ॉल्यूशन सीमा को प्राप्त करता है या सेट करता है। |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | मेटाफाइल रास्टराइजेशन के लिए निचली रिज़ॉल्यूशन सीमा को प्राप्त करता है या सेट करता है। |
| [getDisable3DText()](#getDisable3DText--) | निर्धारित करता है कि SVG में 3D टेक्स्ट अक्षम है या नहीं। |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | निर्धारित करता है कि SVG में 3D टेक्स्ट अक्षम है या नहीं। |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | FromCornerX और FromCenter ग्रेडिएंट्स के विभाजन को अक्षम करता है। |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | FromCornerX और FromCenter ग्रेडिएंट्स के विभाजन को अक्षम करता है। |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 में मार्कर्स के लिए इनसेट निर्धारित करने की क्षमता नहीं है। |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 में मार्कर्स के लिए इनसेट निर्धारित करने की क्षमता नहीं है। |
| [getJpegQuality()](#getJpegQuality--) | JPEG एन्कोडिंग क्वालिटी निर्धारित करता है। |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG एन्कोडिंग क्वालिटी निर्धारित करता है। |
| [getShapeFormattingController()](#getShapeFormattingController--) | एक कॉलबैक इंटरफ़ेस को प्राप्त करता है और सेट करता है जो उपयोगकर्ता को आकार परिवर्तन को नियंत्रित करने की अनुमति देता है। |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | एक कॉलबैक इंटरफ़ेस को प्राप्त करता है और सेट करता है जो उपयोगकर्ता को आकार परिवर्तन को नियंत्रित करने की अनुमति देता है। |
| [getPicturesCompression()](#getPicturesCompression--) | चित्रों की संपीड़न स्तर का प्रतिनिधित्व करता है पढ़ें/लिखें \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | चित्रों की संपीड़न स्तर का प्रतिनिधित्व करता है पढ़ें/लिखें \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | एक बूलियन फ़्लैग दर्शाता है कि क्रॉप किए गए हिस्से दस्तावेज़ का हिस्सा बने रहते हैं या नहीं। |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | एक बूलियन फ़्लैग दर्शाता है कि क्रॉप किए गए हिस्से दस्तावेज़ का हिस्सा बने रहते हैं या नहीं। |
| [getUseFrameSize()](#getUseFrameSize--) | निर्धारित करता है कि टेक्स्ट फ़्रेम को रेंडरिंग क्षेत्र में शामिल किया जाएगा या नहीं। |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | निर्धारित करता है कि टेक्स्ट फ़्रेम को रेंडरिंग क्षेत्र में शामिल किया जाएगा या नहीं। |
| [getUseFrameRotation()](#getUseFrameRotation--) | निर्धारित करता है कि रेंडरिंग के दौरान आकार की निर्दिष्ट घूर्णन को लागू किया जाएगा या नहीं। |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | निर्धारित करता है कि रेंडरिंग के दौरान आकार की निर्दिष्ट घूर्णन को लागू किया जाएगा या नहीं। |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | बाहरी रूप से लोड की गई फ़ॉन्ट्स को संभालने का एक तरीका निर्धारित करता है। |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | बाहरी रूप से लोड की गई फ़ॉन्ट्स को संभालने का एक तरीका निर्धारित करता है। |
| [getInkOptions()](#getInkOptions--) | एक्सपोर्ट किए गए दस्तावेज़ में Ink वस्तुओं के लुक को नियंत्रित करने वाले विकल्प प्रदान करता है। |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | यह प्राप्त करता या सेट करता है कि टेक्स्ट को लिगेचर के बिना रेंडर किया गया है या नहीं। |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | यह प्राप्त करता या सेट करता है कि टेक्स्ट को लिगेचर के बिना रेंडर किया गया है या नहीं। |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

निर्धारित करता है कि स्लाइड पर टेक्स्ट को ग्राफिक्स के रूप में सहेजा जाएगा या नहीं। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

निर्धारित करता है कि स्लाइड पर टेक्स्ट को ग्राफिक्स के रूप में सहेजा जाएगा या नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

मेटाफाइल रास्टराइजेशन के लिए निचली रिज़ॉल्यूशन सीमा को प्राप्त करता है या सेट करता है। पढ़ें/लिखें int.

**रिटर्न:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

मेटाफाइल रास्टराइजेशन के लिए निचली रिज़ॉल्यूशन सीमा को प्राप्त करता है या सेट करता है। पढ़ें/लिखें int.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

निर्धारित करता है कि SVG में 3D टेक्स्ट अक्षम है या नहीं। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

निर्धारित करता है कि SVG में 3D टेक्स्ट अक्षम है या नहीं। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

FromCornerX और FromCenter ग्रेडिएंट्स के विभाजन को अक्षम करता है। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

FromCornerX और FromCenter ग्रेडिएंट्स के विभाजन को अक्षम करता है। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 में मार्कर्स के लिए इनसेट निर्धारित करने की क्षमता नहीं है। Aspose.Slides SVG लेखन इंजन इस समस्या के लिए एक वर्कअराउंड प्रदान करता है: यह तीर वाले लाइन के अंत को क्रॉप कर देता है, ताकि लाइन मार्कर्स के ऊपर नहीं आती। यह विकल्प इस व्यवहार को बंद कर देता है। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 में मार्कर्स के लिए इनसेट निर्धारित करने की क्षमता नहीं है। Aspose.Slides SVG लेखन इंजन इस समस्या के लिए एक वर्कअराउंड प्रदान करता है: यह तीर वाले लाइन के अंत को क्रॉप कर देता है, ताकि लाइन मार्कर्स के ऊपर नहीं आती। यह विकल्प इस व्यवहार को बंद कर देता है। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

JPEG एन्कोडिंग क्वालिटी निर्धारित करता है। पढ़ें/लिखें int.

**रिटर्न:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

JPEG एन्कोडिंग क्वालिटी निर्धारित करता है। पढ़ें/लिखें int.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

एक कॉलबैक इंटरफ़ेस को प्राप्त करता है और सेट करता है जो उपयोगकर्ता को आकार परिवर्तन को नियंत्रित करने की अनुमति देता है। पढ़ें/लिखें [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**रिटर्न:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

एक कॉलबैक इंटरफ़ेस को प्राप्त करता है और सेट करता है जो उपयोगकर्ता को आकार परिवर्तन को नियंत्रित करने की अनुमति देता है। पढ़ें/लिखें [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

चित्रों की संपीड़न स्तर का प्रतिनिधित्व करता है पढ़ें/लिखें \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**रिटर्न:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

चित्रों की संपीड़न स्तर का प्रतिनिधित्व करता है पढ़ें/लिखें \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

एक बूलियन फ़्लैग दर्शाता है कि क्रॉप किए गए हिस्से दस्तावेज़ का हिस्सा बने रहते हैं या नहीं। यदि true है तो क्रॉप किए गए हिस्से हटा दिये जाएंगे, यदि false है तो वे दस्तावेज़ में सीरियलाइज़ हो जाएंगे (जिससे फ़ाइल बड़ा हो सकती है)। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

एक बूलियन फ़्लैग दर्शाता है कि क्रॉप किए गए हिस्से दस्तावेज़ का हिस्सा बने रहते हैं या नहीं। यदि true है तो क्रॉप किए गए हिस्से हटा दिये जाएंगे, यदि false है तो वे दस्तावेज़ में सीरियलाइज़ हो जाएंगे (जिससे फ़ाइल बड़ा हो सकती है)। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

निर्धारित करता है कि टेक्स्ट फ़्रेम को रेंडरिंग क्षेत्र में शामिल किया जाएगा या नहीं। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान false है।

**रिटर्न:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

निर्धारित करता है कि टेक्स्ट फ़्रेम को रेंडरिंग क्षेत्र में शामिल किया जाएगा या नहीं। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान false है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

निर्धारित करता है कि रेंडरिंग के दौरान आकार की निर्दिष्ट घूर्णन को लागू किया जाएगा या नहीं। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान true है।

**रिटर्न:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

निर्धारित करता है कि रेंडरिंग के दौरान आकार की निर्दिष्ट घूर्णन को लागू किया जाएगा या नहीं। पढ़ें/लिखें boolean। डिफ़ॉल्ट मान true है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

बाहरी रूप से लोड की गई फ़ॉन्ट्स को संभालने का एक तरीका निर्धारित करता है। पढ़ें/लिखें [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**रिटर्न:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

बाहरी रूप से लोड की गई फ़ॉन्ट्स को संभालने का एक तरीका निर्धारित करता है। पढ़ें/लिखें [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

एक्सपोर्ट किए गए दस्तावेज़ में Ink वस्तुओं के लुक को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल पढ़ें [IInkOptions](../../com.aspose.slides/iinkoptions)

**रिटर्न:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

यह प्राप्त करता या सेट करता है कि टेक्स्ट को लिगेचर के बिना रेंडर किया गया है या नहीं। जब true सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट है।

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

**रिटर्न:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

यह प्राप्त करता या सेट करता है कि टेक्स्ट को लिगेचर के बिना रेंडर किया गया है या नहीं। जब true सेट किया जाता है, तो रेंडर किए गए आउटपुट में लिगेचर अक्षम हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट है।

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |