---
title: IHtmlFormattingController
second_title: Aspose.Slides for Java API Reference
description: HTML फ़ाइल निर्माण को नियंत्रित करता है।
type: docs
url: /hi/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

HTML फ़ाइल निर्माण को नियंत्रित करता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML दस्तावेज़ शीर्षलेख लिखने के लिए बुलाया जाता है। |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML दस्तावेज़ फुटर लिखने के लिए बुलाया जाता है। |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML स्लाइड शीर्षलेख लिखने के लिए बुलाया जाता है। |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML स्लाइड फुटर लिखने के लिए बुलाया जाता है। |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | शेप के रेंडरिंग से पहले बुलाया जाता है। |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | शेप के रेंडरिंग से पहले बुलाया जाता है। |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

HTML दस्तावेज़ शीर्षलेख लिखने के लिए बुलाया जाता है। प्रस्तुति रूपांतरण के प्रत्येक बार एक बार बुलाया जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | प्रेज़ेंटेशन जो वर्तमान में रेंडर किया जा रहा है। |
### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

HTML दस्तावेज़ फुटर लिखने के लिए बुलाया जाता है। प्रस्तुति रूपांतरण के प्रत्येक बार एक बार बुलाया जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | प्रेज़ेंटेशन जो वर्तमान में रेंडर किया जा रहा है। |
### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

HTML स्लाइड शीर्षलेख लिखने के लिए बुलाया जाता है। प्रत्येक स्लाइड के लिए एक बार बुलाया जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| slide | [ISlide](../../com.aspose.slides/islide) | स्लाइड जो वर्तमान में रेंडर किया जा रहा है। |
### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

HTML स्लाइड फुटर लिखने के लिए बुलाया जाता है। प्रत्येक स्लाइड के लिए एक बार बुलाया जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| slide | [ISlide](../../com.aspose.slides/islide) | स्लाइड जो वर्तमान में रेंडर किया जा रहा है। |
### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

शेप के रेंडरिंग से पहले बुलाया जाता है। प्रत्येक शेप के लिए एक बार बुलाया जाता है। यदि यह फ़ंक्शन जेनरेटर को कुछ लिखता है, तो वर्तमान स्लाइड छवि निर्माण समाप्त हो जाएगा, जोड़ा गया html अंश सम्मिलित हो जाएगा और नई छवि पिछले के ऊपर शुरू होगी।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| shape | [IShape](../../com.aspose.slides/ishape) | शेप जो रेंडर होने वाला है। |
### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

शेप के रेंडरिंग से पहले बुलाया जाता है। प्रत्येक शेप के लिए एक बार बुलाया जाता है। यदि यह फ़ंक्शन जेनरेटर को कुछ लिखता है, वर्तमान स्लाइड छवि निर्माण समाप्त हो जाएगा, जोड़ा गया html अंश सम्मिलित हो जाएगा और नई छवि पिछले के ऊपर शुरू होगी।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| shape | [IShape](../../com.aspose.slides/ishape) | शेप जो अंतिम रूप से रेंडर किया गया है। |