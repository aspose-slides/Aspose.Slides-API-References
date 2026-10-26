---
title: SVGOptions
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक SVG विकल्प का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/svgoptions/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**सभी लागू इंटरफेस:**  
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable  
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

एक SVG विकल्प का प्रतिनिधित्व करता है।

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | SVGOptions क्लास का नया उदाहरण प्रारंभ करता है। |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | लिंक एम्बेडिंग कंट्रोलर ऑब्जेक्ट निर्दिष्ट करते हुए SVGOptions क्लास का नया उदाहरण प्रारंभ करता है। |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | निर्यातित दस्तावेज़ में Ink ऑब्जेक्ट्स की दिखावट को नियंत्रित करने वाले विकल्प प्रदान करता है। |
| [getUseFrameSize()](#getUseFrameSize--) | निर्धारित करता है कि टेक्स्ट फ्रेम को रेंडरिंग क्षेत्र में शामिल किया जाएगा या नहीं। |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | निर्धारित करता है कि टेक्स्ट फ्रेम को रेंडरिंग क्षेत्र में शामिल किया जाएगा या नहीं। |
| [getUseFrameRotation()](#getUseFrameRotation--) | रेंडरिंग के समय आकार की निर्दिष्ट घुमाव को लागू किया जाए या नहीं, यह निर्धारित करता है। |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | रेंडरिंग के समय आकार की निर्दिष्ट घुमाव को लागू किया जाए या नहीं, यह निर्धारित करता है। |
| [getVectorizeText()](#getVectorizeText--) | निर्धारित करता है कि स्लाइड पर मौजूद टेक्स्ट को ग्राफ़िक्स के रूप में सहेजा जाएगा या नहीं। |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | निर्धारित करता है कि स्लाइड पर मौजूद टेक्स्ट को ग्राफ़िक्स के रूप में सहेजा जाएगा या नहीं। |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | मेटाफाइल रास्टराइज़ेशन के लिए निचली रिज़ॉल्यूशन सीमा को प्राप्त या सेट करता है। |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | मेटाफाइल रास्टराइज़ेशन के लिए निचली रिज़ॉल्यूशन सीमा को प्राप्त या सेट करता है। |
| [getDisable3DText()](#getDisable3DText--) | निर्धारित करता है कि SVG में 3D टेक्स्ट निष्क्रिय है या नहीं। |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | निर्धारित करता है कि SVG में 3D टेक्स्ट निष्क्रिय है या नहीं। |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | FromCornerX और FromCenter ग्रेडिएंट्स के विभाजन को निष्क्रिय करता है। |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | FromCornerX और FromCenter ग्रेडिएंट्स के विभाजन को निष्क्रिय करता है। |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 में मार्कर्स के लिए इनसेट परिभाषित करने की क्षमता नहीं है। |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 में मार्कर्स के लिए इनसेट परिभाषित करने की क्षमता नहीं है। |
| [getDefault()](#getDefault--) | डिफ़ॉल्ट सेटिंग्स को प्राप्त करता है। |
| [getSimple()](#getSimple--) | सबसे सरल और सबसे छोटे SVG फ़ाइल निर्माण के लिए सेटिंग्स को प्राप्त करता है। |
| [getWYSIWYG()](#getWYSIWYG--) | सबसे सटीक SVG फ़ाइल निर्माण के लिए सेटिंग्स को प्राप्त करता है। |
| [getJpegQuality()](#getJpegQuality--) | JPEG एन्कोडिंग गुणवत्ता को निर्धारित करता है। |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG एन्कोडिंग गुणवत्ता को निर्धारित करता है। |
| [getShapeFormattingController()](#getShapeFormattingController--) | एक कॉलबैक इंटरफ़ेस को प्राप्त और सेट करता है जो उपयोगकर्ता को आकार परिवर्तन को नियंत्रित करने की अनुमति देता है। |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | एक कॉलबैक इंटरफ़ेस को प्राप्त और सेट करता है जो उपयोगकर्ता को आकार परिवर्तन को नियंत्रित करने की अनुमति देता है। |
| [getPicturesCompression()](#getPicturesCompression--) | चित्र संपीड़न स्तर का प्रतिनिधित्व करता है |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | चित्र संपीड़न स्तर का प्रतिनिधित्व करता है |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | एक बूलियन फ़्लैग दर्शाता है कि क्रॉप किए गए भाग दस्तावेज़ का हिस्सा बने रहते हैं। |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | एक बूलियन फ़्लैग दर्शाता है कि क्रॉप किए गए भाग दस्तावेज़ का हिस्सा बने रहते हैं। |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | बाहरी लोड किए गए फ़ॉन्ट्स को संभालने का तरीका निर्धारित करता है। |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | बाहरी लोड किए गए फ़ॉन्ट्स को संभालने का तरीका निर्धारित करता है। |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | यह निर्धारित करता है कि टेक्स्ट को लिगेचर के बिना रेंडर किया जाए या नहीं। |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | यह निर्धारित करता है कि टेक्स्ट को लिगेचर के बिना रेंडर किया जाए या नहीं। |

### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

SVGOptions क्लास का नया उदाहरण प्रारंभ करता है।

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

लिंक एम्बेडिंग कंट्रोलर ऑब्जेक्ट निर्दिष्ट करते हुए SVGOptions क्लास का नया उदाहरण प्रारंभ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | लिंक एम्बेडिंग कंट्रोलर संदर्भ।

--------------------

लिंक एम्बेडिंग कंट्रोलर एक डेलीgate ऑब्जेक्ट है जो यह निर्धारित करता है कि संसाधनों (जैसे छवियों) को एम्बेड किया जाए या बाहरी संसाधन के रूप में संदर्भित किया जाए। |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

निर्यातित दस्तावेज़ में Ink ऑब्जेक्ट्स की दिखावट को नियंत्रित करने वाले विकल्प प्रदान करता है। केवल पढ़ने योग्य [IInkOptions](../../com.aspose.slides/iinkoptions)

**वापसी:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

निर्धारित करता है कि टेक्स्ट फ्रेम को रेंडरिंग क्षेत्र में शामिल किया जाएगा या नहीं। पढ़ने/लिखने योग्य बूलियन। डिफ़ॉल्ट मान false है।

**वापसी:**
boolean

### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

निर्धारित करता है कि टेक्स्ट फ्रेम को रेंडरिंग क्षेत्र में शामिल किया जाएगा या नहीं। पढ़ने/लिखने योग्य बूलियन। डिफ़ॉल्ट मान false है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

रेंडरिंग के समय आकार की निर्दिष्ट घुमाव को लागू किया जाए या नहीं, यह निर्धारित करता है। पढ़ने/लिखने योग्य बूलियन। डिफ़ॉल्ट मान true है।

**वापसी:**
boolean

### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

रेंडरिंग के समय आकार की निर्दिष्ट घुमाव को लागू किया जाए या नहीं, यह निर्धारित करता है। पढ़ने/लिखने योग्य बूलियन। डिफ़ॉल्ट मान true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

निर्धारित करता है कि स्लाइड पर मौजूद टेक्स्ट को ग्राफ़िक्स के रूप में सहेजा जाएगा या नहीं। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean

### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

निर्धारित करता है कि स्लाइड पर मौजूद टेक्स्ट को ग्राफ़िक्स के रूप में सहेजा जाएगा या नहीं। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

मेटाफाइल रास्टराइज़ेशन के लिए निचली रिज़ॉल्यूशन सीमा को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य int।

**वापसी:**
int

### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

मेटाफाइल रास्टराइज़ेशन के लिए निचली रिज़ॉल्यूशन सीमा को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

निर्धारित करता है कि SVG में 3D टेक्स्ट निष्क्रिय है या नहीं। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean

### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

निर्धारित करता है कि SVG में 3D टेक्स्ट निष्क्रिय है या नहीं। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

FromCornerX और FromCenter ग्रेडिएंट्स के विभाजन को निष्क्रिय करता है। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean

### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

FromCornerX और FromCenter ग्रेडिएंट्स के विभाजन को निष्क्रिय करता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 में मार्कर्स के लिए इनसेट परिभाषित करने की क्षमता नहीं है। Aspose.Slides SVG लेखन इंजन इस समस्या के लिए एक वर्कअराउंड प्रदान करता है: यह तीर के साथ लाइन के अंत को क्रॉप करता है, ताकि लाइन मार्कर्स के ऊपर न आए। यह विकल्प इस व्यवहार को बंद करता है। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean

### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 में मार्कर्स के लिए इनसेट परिभाषित करने की क्षमता नहीं है। Aspose.Slides SVG लेखन इंजन इस समस्या के लिए एक वर्कअराउंड प्रदान करता है: यह तीर के साथ लाइन के अंत को क्रॉप करता है, ताकि लाइन मार्कर्स के ऊपर न आए। यह विकल्प इस व्यवहार को बंद करता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

डिफ़ॉल्ट सेटिंग्स को प्राप्त करता है। केवल पढ़ने योग्य [SVGOptions](../../com.aspose.slides/svgoptions)।

**वापसी:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

सबसे सरल और सबसे छोटे SVG फ़ाइल निर्माण के लिए सेटिंग्स को प्राप्त करता है। केवल पढ़ने योग्य [SVGOptions](../../com.aspose.slides/svgoptions)।

**वापसी:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

सबसे सटीक SVG फ़ाइल निर्माण के लिए सेटिंग्स को प्राप्त करता है। केवल पढ़ने योग्य [SVGOptions](../../com.aspose.slides/svgoptions)।

**वापसी:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

JPEG एन्कोडिंग गुणवत्ता को निर्धारित करता है। पढ़ने/लिखने योग्य int।

**वापसी:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

JPEG एन्कोडिंग गुणवत्ता को निर्धारित करता है। पढ़ने/लिखने योग्य int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

आकार परिवर्तन को नियंत्रित करने की अनुमति देने वाला कॉलबैक इंटरफ़ेस प्राप्त और सेट करता है। पढ़ने/लिखने योग्य [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)।

**वापसी:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)

### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

आकार परिवर्तन को नियंत्रित करने की अनुमति देने वाला कॉलबैक इंटरफ़ेस प्राप्त और सेट करता है। पढ़ने/लिखने योग्य [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

चित्र संपीड़न स्तर का प्रतिनिधित्व करता है

**वापसी:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

चित्र संपीड़न स्तर का प्रतिनिधित्व करता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

एक बूलियन फ़्लैग दर्शाता है कि क्रॉप किए गए भाग दस्तावेज़ का हिस्सा बने रहते हैं। यदि true है तो क्रॉप किए गए भाग हटा दिए जाते हैं, यदि false है तो वे दस्तावेज़ में क्रमबद्ध रहेंगे (जिससे फ़ाइल आकार बढ़ सकता है)

**वापसी:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

एक बूलियन फ़्लैग दर्शाता है कि क्रॉप किए गए भाग दस्तावेज़ का हिस्सा बने रहते हैं। यदि true है तो क्रॉप किए गए भाग हटा दिए जाते हैं, यदि false है तो वे दस्तावेज़ में क्रमबद्ध रहेंगे (जिससे फ़ाइल आकार बढ़ सकता है)

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

बाहरी लोड किए गए फ़ॉन्ट्स को संभालने का तरीका निर्धारित करता है। पढ़ने/लिखने योग्य [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling)।

**वापसी:**
int

### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

बाहरी लोड किए गए फ़ॉन्ट्स को संभालने का तरीका निर्धारित करता है। पढ़ने/लिखने योग्य [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

पाठ को लिगेचर के बिना रेंडर किया जाए या नहीं, यह निर्धारित करने के लिए मान प्राप्त या सेट करता है। यदि true पर सेट किया जाता है, तो लिगेचर रेंडर आउटपुट में निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट है।

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
public final void setDisableFontLigatures(boolean value)
```

पाठ को लिगेचर के बिना रेंडर किया जाए या नहीं, यह निर्धारित करने के लिए मान प्राप्त या सेट करता है। यदि true पर सेट किया जाता है, तो लिगेचर रेंडर आउटपुट में निष्क्रिय हो जाएंगे। डिफ़ॉल्ट रूप से, यह प्रॉपर्टी false पर सेट है।

--------------------

> ```
public final void setDisableFontLigatures(boolean value)
```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |