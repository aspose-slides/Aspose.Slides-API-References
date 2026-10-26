---
title: SVGOptions
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: SVG विकल्पों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/svgoptions/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**सभी कार्यान्वित इंटरफ़ेस:**  
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable  
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

SVG विकल्पों का प्रतिनिधित्व करता है।

## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | SVGOptions क्लास का नया उदाहरण प्रारम्भ करता है। |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | SVGOptions क्लास का नया उदाहरण प्रारम्भ करता है, लिंक एम्बेडिंग कंट्रोलर ऑब्जेक्ट निर्दिष्ट करता है। |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | निर्यात किए गए दस्तावेज़ में Ink ऑब्जेक्ट्स की उपस्थिति को नियंत्रित करने वाले विकल्प प्रदान करता है। |
| [getUseFrameSize()](#getUseFrameSize--) | निर्धारित करता है कि क्या टेक्स्ट फ्रेम को रेंडरिंग क्षेत्र में शामिल किया जाए या नहीं। |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | निर्धारित करता है कि क्या टेक्स्ट फ्रेम को रेंडरिंग क्षेत्र में शामिल किया जाए या नहीं। |
| [getUseFrameRotation()](#getUseFrameRotation--) | निर्धारित करता है कि रेंडरिंग के दौरान आकार की निर्दिष्ट घुमाव को लागू किया जाए या नहीं। |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | निर्धारित करता है कि रेंडरिंग के दौरान आकार की निर्दिष्ट घुमाव को लागू किया जाए या नहीं। |
| [getVectorizeText()](#getVectorizeText--) | निर्धारित करता है कि स्लाइड पर टेक्स्ट को ग्राफ़िक्स के रूप में सहेजा जाए या नहीं। |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | निर्धारित करता है कि स्लाइड पर टेक्स्ट को ग्राफ़िक्स के रूप में सहेजा जाए या नहीं। |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | मेटाफाइल रास्टराइज़ेशन के लिए निचली रेज़ोल्यूशन सीमा को वापस करता है या सेट करता है। |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | मेटाफाइल रास्टराइज़ेशन के लिए निचली रेज़ोल्यूशन सीमा को वापस करता है या सेट करता है। |
| [getDisable3DText()](#getDisable3DText--) | निर्धारित करता है कि SVG में 3D टेक्स्ट निष्क्रिय है या नहीं। |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | निर्धारित करता है कि SVG में 3D टेक्स्ट निष्क्रिय है या नहीं। |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | FromCornerX और FromCenter ग्रेडिएंट्स के विभाजन को निष्क्रिय करता है। |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | FromCornerX और FromCenter ग्रेडिएंट्स के विभाजन को निष्क्रिय करता है। |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 में मार्करों के लिए इनसेट परिभाषित करने की क्षमता नहीं है। |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 में मार्करों के लिए इनसेट परिभाषित करने की क्षमता नहीं है। |
| [getDefault()](#getDefault--) | डिफ़ॉल्ट सेटिंग्स को वापस करता है। |
| [getSimple()](#getSimple--) | सबसे सरल और सबसे छोटे SVG फ़ाइल जनरेशन के लिए सेटिंग्स को वापस करता है। |
| [getWYSIWYG()](#getWYSIWYG--) | सबसे सटीक SVG फ़ाइल जनरेशन के लिए सेटिंग्स को वापस करता है। |
| [getJpegQuality()](#getJpegQuality--) | JPEG एन्कोडिंग गुणवत्ता निर्धारित करता है। |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG एन्कोडिंग गुणवत्ता निर्धारित करता है। |
| [getShapeFormattingController()](#getShapeFormattingController--) | एक कॉलबैक इंटरफ़ेस को वापस करता है और सेट करता है जो उपयोगकर्ता को आकार रूपांतरण को नियंत्रित करने की अनुमति देता है। |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | एक कॉलबैक इंटरफ़ेस को वापस करता है और सेट करता है जो उपयोगकर्ता को आकार रूपांतरण को नियंत्रित करने की अनुमति देता है। |
| [getPicturesCompression()](#getPicturesCompression--) | चित्रों के संपीड़न स्तर का प्रतिनिधित्व करता है |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | चित्रों के संपीड़न स्तर का प्रतिनिधित्व करता है |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | एक बूलियन फ़्लैग यह संकेत देता है कि कटे हुए भाग दस्तावेज़ का हिस्सा बने रहें या नहीं। |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | एक बूलियन फ़्लैग यह संकेत देता है कि कटे हुए भाग दस्तावेज़ का हिस्सा बने रहें या नहीं। |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | बाहरी लोड किए गए फ़ॉन्ट्स को संभालने का तरीका निर्धारित करता है। |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | बाहरी लोड किए गए फ़ॉन्ट्स को संभालने का तरीका निर्धारित करता है। |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | टेक्स्ट को बिना लिगेचर के रेंडर किया जाए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | टेक्स्ट को बिना लिगेचर के रेंडर किया जाए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |

### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

SVGOptions क्लास का नया उदाहरण प्रारम्भ करता है।

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

SVGOptions क्लास का नया उदाहरण प्रारम्भ करता है, लिंक एम्बेडिंग कंट्रोलर ऑब्जेक्ट निर्दिष्ट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | लिंक एम्बेडिंग कंट्रोलर संदर्भ। |

--------------------

Link embedding controller is a delegate object that is responsible for making decisions if resources (such as images) need to be embedded or referenced as external resources. |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

निर्यात किए गए दस्तावेज़ में Ink ऑब्जेक्ट्स की उपस्थिति को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल-पढ़ने योग्य [IInkOptions](../../com.aspose.slides/iinkoptions)

**वापसी मान:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

निर्धारित करता है कि क्या टेक्स्ट फ्रेम को रेंडरिंग क्षेत्र में शामिल किया जाए या नहीं। पढ़ने/लिखने योग्य बूलियन। डिफ़ॉल्ट मान false है।

**वापसी मान:**
boolean

### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

निर्धारित करता है कि क्या टेक्स्ट फ्रेम को रेंडरिंग क्षेत्र में शामिल किया जाए या नहीं। पढ़ने/लिखने योग्य बूलियन। डिफ़ॉल्ट मान false है।

**पैरामीटर:**
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

निर्धारित करता है कि रेंडरिंग के दौरान आकार की निर्दिष्ट घुमाव को लागू किया जाए या नहीं। पढ़ने/लिखने योग्य बूलियन। डिफ़ॉल्ट मान true है।

**वापसी मान:**
boolean

### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

निर्धारित करता है कि रेंडरिंग के दौरान आकार की निर्दिष्ट घुमाव को लागू किया जाए या नहीं। पढ़ने/लिखने योग्य बूलियन। डिफ़ॉल्ट मान true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

निर्धारित करता है कि स्लाइड पर टेक्स्ट को ग्राफ़िक्स के रूप में सहेजा जाए या नहीं। पढ़ने/लिखने योग्य बूलियन।

**वापसी मान:**
boolean

### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

निर्धारित करता है कि स्लाइड पर टेक्स्ट को ग्राफ़िक्स के रूप में सहेजा जाए या नहीं। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

मेटाफाइल रास्टराइज़ेशन के लिए निचली रेज़ोल्यूशन सीमा को वापस करता है या सेट करता है। पढ़ने/लिखने योग्य int।

**वापसी मान:**
int

### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

मेटाफाइल रास्टराइज़ेशन के लिए निचली रेज़ोल्यूशन सीमा को वापस करता है या सेट करता है। पढ़ने/लिखने योग्य int।

**पैरामीटर:**
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

निर्धारित करता है कि SVG में 3D टेक्स्ट निष्क्रिय है या नहीं। पढ़ने/लिखने योग्य बूलियन।

**वापसी मान:**
boolean

### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

निर्धारित करता है कि SVG में 3D टेक्स्ट निष्क्रिय है या नहीं। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

FromCornerX और FromCenter ग्रेडिएंट्स के विभाजन को निष्क्रिय करता है। पढ़ने/लिखने योग्य बूलियन।

**वापसी मान:**
boolean

### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

FromCornerX और FromCenter ग्रेडिएंट्स के विभाजन को निष्क्रिय करता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 में मार्करों के लिए इनसेट परिभाषित करने की क्षमता नहीं है। Aspose.Slides SVG लिखने वाला इंजन इस समस्या के लिए वर्कअराउंड प्रदान करता है: यह तीर वाले लाइन के अंत को क्रॉप करता है, जिससे लाइन मार्करों के साथ ओवरलैप न करे। यह विकल्प इस व्यवहार को बंद करता है। पढ़ने/लिखने योग्य बूलियन।

**वापसी मान:**
boolean

### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 में मार्करों के लिए इनसेट परिभाषित करने की क्षमता नहीं है। Aspose.Slides SVG लिखने वाला इंजन इस समस्या के लिए वर्कअराउंड प्रदान करता है: यह तीर वाले लाइन के अंत को क्रॉप करता है, जिससे लाइन मार्करों के साथ ओवरलैप न करे। यह विकल्प इस व्यवहार को बंद करता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

डिफ़ॉल्ट सेटिंग्स को वापस करता है। केवल-पढ़ने योग्य [SVGOptions](../../com.aspose.slides/svgoptions)।

**वापसी मान:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

सबसे सरल और सबसे छोटे SVG फ़ाइल जनरेशन के लिए सेटिंग्स को वापस करता है। केवल-पढ़ने योग्य [SVGOptions](../../com.aspose.slides/svgoptions)।

**वापसी मान:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

सबसे सटीक SVG फ़ाइल जनरेशन के लिए सेटिंग्स को वापस करता है। केवल-पढ़ने योग्य [SVGOptions](../../com.aspose.slides/svgoptions)।

**वापसी मान:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

JPEG एन्कोडिंग गुणवत्ता निर्धारित करता है। पढ़ने/लिखने योग्य int।

**वापसी मान:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

JPEG एन्कोडिंग गुणवत्ता निर्धारित करता है। पढ़ने/लिखने योग्य int।

**पैरामीटर:**
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

एक कॉलबैक इंटरफ़ेस को वापस करता है और सेट करता है जो उपयोगकर्ता को आकार रूपांतरण को नियंत्रित करने की अनुमति देता है। पढ़ने/लिखने योग्य [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)।

**वापसी मान:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)

### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

एक कॉलबैक इंटरफ़ेस को वापस करता है और सेट करता है जो उपयोगकर्ता को आकार रूपांतरण को नियंत्रित करने की अनुमति देता है। पढ़ने/लिखने योग्य [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)।

**पैरामीटर:**
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

चित्रों के संपीड़न स्तर का प्रतिनिधित्व करता है

**वापसी मान:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

चित्रों के संपीड़न स्तर का प्रतिनिधित्व करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

एक बूलियन फ़्लैग यह संकेत देता है कि कटे हुए भाग दस्तावेज़ का हिस्सा बने रहें या नहीं। यदि true हो तो कटे हुए भाग हटा दिए जाएंगे, यदि false हो तो वे दस्तावेज़ में सीरियलाइज़ किए जाएंगे (जिससे फ़ाइल आकार बड़ा हो सकता है)

**वापसी मान:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

एक बूलियन फ़्लैग यह संकेत देता है कि कटे हुए भाग दस्तावेज़ का हिस्सा बने रहें या नहीं। यदि true हो तो कटे हुए भाग हटा दिए जाएंगे, यदि false हो तो वे दस्तावेज़ में सीरियलाइज़ किए जाएंगे (जिससे फ़ाइल आकार बड़ा हो सकता है)

**पैरामीटर:**
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

बाहरी लोड किए गए फ़ॉन्ट्स को संभालने का तरीका निर्धारित करता है। पढ़ने/लिखने योग्य [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling)।

**वापसी मान:**
int

### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

बाहरी लोड किए गए फ़ॉन्ट्स को संभालने का तरीका निर्धारित करता है। पढ़ने/लिखने योग्य [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling)।

**पैरामीटर:**
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

टेक्स्ट को बिना लिगेचर के रेंडर किया जाए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। जब true पर सेट किया जाता है, लिगेचर रेंडर किए गए आउटपुट में निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट होती है।

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

**वापसी मान:**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

टेक्स्ट को बिना लिगेचर के रेंडर किया जाए यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। जब true पर सेट किया जाता है, लिगेचर रेंडर किए गए आउटपुट में निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट होती है।

> ```
> उदाहरण:
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
| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| value | boolean |  |