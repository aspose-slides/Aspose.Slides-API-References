---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides for Java API संदर्भ
description: WOFF फ़ॉर्मेट में सभी प्रस्तुति फ़ॉन्ट को एम्बेड करने के लिए उपयोग किया जाने वाला फ़ॉर्मेटिंग कंट्रोलर क्लास।
type: docs
url: /hi/com.aspose.slides/embedallfontshtmlcontroller/
---
**Inheritance:**  
वंशानुक्रम:

java.lang.Object

**All Implemented Interfaces:**  
सभी लागू इंटरफ़ेस:

[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

फ़ॉर्मेटिंग कंट्रोलर क्लास जिसका उपयोग सभी प्रस्तुति फ़ॉन्ट को WOFF फ़ॉर्मेट में एम्बेड करने के लिए किया जाता है।
## Constructors

| Constructor | Description |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | नया इंस्टेंस बनाता है |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | नया इंस्टेंस बनाता है |
## Methods

| Method | Description |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML दस्तावेज़ हेडर लिखने के लिए बुलाया जाता है। |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML दस्तावेज़ फुटर लिखने के लिए बुलाया जाता है। |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML स्लाइड हेडर लिखने के लिए बुलाया जाता है। |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML स्लाइड फुटर लिखने के लिए बुलाया जाता है। |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | शेप के रेंडरिंग से पहले बुलाया जाता है। |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | शेप के रेंडरिंग से पहले बुलाया जाता है। |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | [Presentation](../../com.aspose.slides/presentation) में शामिल सभी फ़ॉन्ट लिखें। |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | डेटा को base64 के रूप में HTML दस्तावेज़ में लिखता है |
### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```


नया इंस्टेंस बनाता है

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```


नया इंस्टेंस बनाता है

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | एम्बेडिंग से बाहर किए जाने वाले फ़ॉन्ट |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


HTML दस्तावेज़ हेडर लिखने के लिए बुलाया जाता है। प्रस्तुति रूपांतरण के दौरान एक बार कॉल किया जाता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | वर्तमान में रेंडर किया जा रहा प्रस्तुतीकरण। |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


HTML दस्तावेज़ फुटर लिखने के लिए बुलाया जाता है। प्रस्तुति रूपांतरण के दौरान एक बार कॉल किया जाता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | वर्तमान में रेंडर किया जा रहा प्रस्तुतीकरण। |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


HTML स्लाइड हेडर लिखने के लिए बुलाया जाता है। प्रत्येक स्लाइड के लिए एक बार कॉल किया जाता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| slide | [ISlide](../../com.aspose.slides/islide) | वर्तमान में रेंडर की जा रही स्लाइड। |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


HTML स्लाइड फुटर लिखने के लिए बुलाया जाता है। प्रत्येक स्लाइड के लिए एक बार कॉल किया जाता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| slide | [ISlide](../../com.aspose.slides/islide) | वर्तमान में रेंडर की जा रही स्लाइड। |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


शेप के रेंडरिंग से पहले बुलाया जाता है। प्रत्येक शेप के लिए एक बार कॉल किया जाता है। यदि यह फ़ंक्शन जनरेटर में कुछ लिखता है, तो वर्तमान स्लाइड इमेज जेनरेशन समाप्त हो जाएगा, जोड़ा गया HTML फ़्रैगमेंट सम्मिलित होगा और नया इमेज पिछले के ऊपर शुरू किया जाएगा।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| shape | [IShape](../../com.aspose.slides/ishape) | वह शेप जो रेंडर होने वाला है। |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


शेप के रेंडरिंग से पहले बुलाया जाता है। प्रत्येक शेप के लिए एक बार कॉल किया जाता है। यदि यह फ़ंक्शन जनरेटर में कुछ लिखता है, तो वर्तमान स्लाइड इमेज जेनरेशन समाप्त हो जाएगा, जोड़ा गया HTML फ़्रैगमेंट सम्मिलित होगा और नया इमेज पिछले के ऊपर शुरू किया जाएगा।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| shape | [IShape](../../com.aspose.slides/ishape) | वह शेप जो अंतिम रूप से रेंडर किया गया। |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```


[Presentation](../../com.aspose.slides/presentation) में शामिल सभी फ़ॉन्ट लिखें।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | वर्तमान में रेंडर किया जा रहा प्रस्तुतीकरण। |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```


डेटा को base64 के रूप में HTML दस्तावेज़ में लिखता है

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | HTML जनरेटर |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | क्रमबद्ध करने के लिए फ़ॉन्ट |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | प्रतिस्थापित फ़ॉन्ट (यदि फ़ॉन्ट प्रतिस्थापन हुआ हो), अन्यथा null |
| fontStyle | java.lang.String | फ़ॉन्ट शैली |
| fontWeight | java.lang.String | फ़ॉन्ट वजन |
| fontData | byte[] | फ़ॉन्ट डेटा |