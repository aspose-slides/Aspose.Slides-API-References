---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides Android के लिए Java API संदर्भ के माध्यम से
description: सभी प्रस्तुति फ़ॉन्ट्स को WOFF प्रारूप में एम्बेड करने के लिए उपयोग किया जाने वाला फ़ॉर्मेटिंग कंट्रोलर क्लास।
type: docs
url: /hi/com.aspose.slides/embedallfontshtmlcontroller/
---
**विरासत:**
java.lang.Object

**सभी लागू किए गए इंटरफ़ेस:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

सभी प्रस्तुति फ़ॉन्ट्स को WOFF प्रारूप में एम्बेड करने के लिए उपयोग किया जाने वाला फ़ॉर्मेटिंग कंट्रोलर क्लास।
## निर्माता

| Constructor | Description |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | नया इंस्टेंस बनाता है |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | नया इंस्टेंस बनाता है |
## विधियाँ

| Method | Description |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML दस्तावेज़ हेडर लिखने के लिए बुलाया जाता है। |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML दस्तावेज़ फुटर लिखने के लिए बुलाया जाता है। |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML स्लाइड हेडर लिखने के लिए बुलाया जाता है। |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML स्लाइड फुटर लिखने के लिए बुलाया जाता है। |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | आकार के रेंडरिंग से पहले बुलाया जाता है। |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | आकार के रेंडरिंग से पहले बुलाया जाता है। |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | सभी फ़ॉन्ट लिखें जो [Presentation](../../com.aspose.slides/presentation) में शामिल हैं। |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | डेटा को base64 के रूप में HTML दस्तावेज़ में स्वयं लिखता है |
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

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | फ़ॉन्ट्स जिन्हें एम्बेड करने से बाहर रखा जाना है |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


HTML दस्तावेज़ हेडर लिखने के लिए बुलाया जाता है। प्रस्तुति रूपांतरण के प्रत्येक बार एक बार बुलाया जाता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | वर्तमान में रेंडर किया जा रहा प्रस्तुति। |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


HTML दस्तावेज़ फुटर लिखने के लिए बुलाया जाता है। प्रस्तुति रूपांतरण के प्रत्येक बार एक बार बुलाया जाता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | वर्तमान में रेंडर किया जा रहा प्रस्तुति। |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


HTML स्लाइड हेडर लिखने के लिए बुलाया जाता है। प्रत्येक स्लाइड के लिए एक बार बुलाया जाता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| slide | [ISlide](../../com.aspose.slides/islide) | स्लाइड जो वर्तमान में रेंडर हो रही है। |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


HTML स्लाइड फुटर लिखने के लिए बुलाया जाता है। प्रत्येक स्लाइड के लिए एक बार बुलाया जाता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| slide | [ISlide](../../com.aspose.slides/islide) | स्लाइड जो वर्तमान में रेंडर हो रही है। |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


आकार के रेंडरिंग से पहले बुलाया जाता है। प्रत्येक आकार के लिए एक बार बुलाया जाता है। यदि यह फ़ंक्शन जेनरेटर में कुछ लिखता है, तो वर्तमान स्लाइड इमेज जनरेशन समाप्त हो जाएगी, जोड़ा गया HTML फ्रैगमेंट सम्मिलित किया जाएगा और नया इमेज पिछले के ऊपर शुरू होगा।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| shape | [IShape](../../com.aspose.slides/ishape) | आकार जो रेंडर होने वाला है। |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


आकार के रेंडरिंग से पहले बुलाया जाता है। प्रत्येक आकार के लिए एक बार बुलाया जाता है। यदि यह फ़ंक्शन जेनरेटर में कुछ लिखता है, तो वर्तमान स्लाइड इमेज जनरेशन समाप्त हो जाएगी, जोड़ा गया HTML फ्रैगमेंट सम्मिलित किया जाएगा और नया इमेज पिछले के ऊपर शुरू होगा।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| shape | [IShape](../../com.aspose.slides/ishape) | अंतिम रेंडर किया गया आकार। |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```


सभी फ़ॉन्ट लिखें जो [Presentation](../../com.aspose.slides/presentation) में शामिल हैं।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | वर्तमान में रेंडर किया जा रहा प्रस्तुति। |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```


डेटा को base64 के रूप में HTML दस्तावेज़ में स्वयं लिखता है

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | HTML जेनरेटर |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | सीरियलाइज़ किया जाने वाला फ़ॉन्ट |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | स्थापित फ़ॉन्ट (यदि फ़ॉन्ट प्रतिस्थापन हुआ है), अन्यथा null |
| fontStyle | java.lang.String | फ़ॉन्ट शैली |
| fontWeight | java.lang.String | फ़ॉन्ट वजन |
| fontData | byte[] | फ़ॉन्ट डेटा |