---
title: ResponsiveHtmlController
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: प्रतिक्रियाशील HTML नियंत्रक
type: docs
url: /hi/com.aspose.slides/responsivehtmlcontroller/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IResponsiveHtmlController](../../com.aspose.slides/iresponsivehtmlcontroller)
```
public class ResponsiveHtmlController implements IResponsiveHtmlController
```

Responsive HTML Controller
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [ResponsiveHtmlController()](#ResponsiveHtmlController--) | एक नया उदाहरण बनाता है |
| [ResponsiveHtmlController(IHtmlFormattingController controller)](#ResponsiveHtmlController-com.aspose.slides.IHtmlFormattingController-) | एक नया उदाहरण बनाता है |
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
### ResponsiveHtmlController() {#ResponsiveHtmlController--}
```
public ResponsiveHtmlController()
```

एक नया उदाहरण बनाता है

### ResponsiveHtmlController(IHtmlFormattingController controller) {#ResponsiveHtmlController-com.aspose.slides.IHtmlFormattingController-}
```
public ResponsiveHtmlController(IHtmlFormattingController controller)
```

एक नया उदाहरण बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| controller | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | HTML फ़ॉर्मेटिंग नियंत्रक |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

HTML दस्तावेज़ शीर्षलेखा लिखने के लिए बुलाया जाता है। प्रस्तुति रूपांतरण के प्रति एक बार बुलाया जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

HTML दस्तावेज़ फुटर लिखने के लिए बुलाया जाता है। प्रस्तुति रूपांतरण के प्रति एक बार बुलाया जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

HTML स्लाइड शीर्षलेखा लिखने के लिए बुलाया जाता है। प्रत्येक स्लाइड के लिये एक बार बुलाया जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

HTML स्लाइड फुटर लिखने के लिए बुलाया जाता है। प्रत्येक स्लाइड के लिये एक बार बुलाया जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

शेप के रेंडरिंग से पहले बुलाया जाता है। प्रत्येक शेप के लिये एक बार बुलाया जाता है। यदि यह फ़ंक्शन जेनरेटर में कुछ लिखता है, तो वर्तमान स्लाइड इमेज जेनरेशन समाप्त हो जाएगी, जोड़ा गया HTML फ्रैगमेंट सम्मिलित होगा और नई इमेज पिछली के ऊपर शुरू होगी।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

शेप के रेंडरिंग से पहले बुलाया जाता है। प्रत्येक शेप के लिये एक बार बुलाया जाता है। यदि यह फ़ंक्शन जेनरेटर में कुछ लिखता है, तो वर्तमान स्लाइड इमेज जेनरेशन समाप्त हो जाएगी, जोड़ा गया HTML फ्रैगमेंट सम्मिलित होगा और नई इमेज पिछली के ऊपर शुरू होगी।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |