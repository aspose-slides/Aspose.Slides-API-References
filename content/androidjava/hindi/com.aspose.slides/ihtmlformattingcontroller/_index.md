---
title: IHtmlFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: html फ़ाइल निर्माण को नियंत्रित करता है।
type: docs
url: /hi/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

html फ़ाइल निर्माण को नियंत्रित करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | html दस्तावेज़ हेडर लिखने के लिए कॉल किया जाता है। |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | html दस्तावेज़ फुटर लिखने के लिए कॉल किया जाता है। |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | html स्लाइड हेडर लिखने के लिए कॉल किया जाता है। |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | html स्लाइड फुटर लिखने के लिए कॉल किया जाता है। |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | shape की रेंडरिंग से पहले कॉल किया जाता है। |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | shape की रेंडरिंग से पहले कॉल किया जाता है। |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

html दस्तावेज़ हेडर लिखने के लिए कॉल किया जाता है। प्रस्तुति रूपांतरण के प्रति एक बार कॉल किया जाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | वर्तमान में रेंडर की जा रही प्रस्तुति। |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

html दस्तावेज़ फुटर लिखने के लिए कॉल किया जाता है। प्रस्तुति रूपांतरण के प्रति एक बार कॉल किया जाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | वर्तमान में रेंडर की जा रही प्रस्तुति। |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

html स्लाइड हेडर लिखने के लिए कॉल किया जाता है। प्रत्येक स्लाइड के लिए एक बार कॉल किया जाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| slide | [ISlide](../../com.aspose.slides/islide) | वर्तमान में रेंडर की जा रही स्लाइड। |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

html स्लाइड फुटर लिखने के लिए कॉल किया जाता है। प्रत्येक स्लाइड के लिए एक बार कॉल किया जाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| slide | [ISlide](../../com.aspose.slides/islide) | वर्तमान में रेंडर की जा रही स्लाइड। |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

shape की रेंडरिंग से पहले कॉल किया जाता है। प्रत्येक shape के लिए एक बार कॉल किया जाता है। यदि यह फ़ंक्शन जेनरेटर में कुछ भी लिखता है, तो वर्तमान स्लाइड इमेज जनरेशन समाप्त हो जाएगी, जोड़ी गई html फ्रैगमेंट सम्मिलित होगी और नई इमेज पिछले के ऊपर शुरू होगी।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| shape | [IShape](../../com.aspose.slides/ishape) | रेंडर होने वाली shape। |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

shape की रेंडरिंग से पहले कॉल किया जाता है। प्रत्येक shape के लिए एक बार कॉल किया जाता है। यदि यह फ़ंक्शन जेनरेटर में कुछ भी लिखता है, तो वर्तमान स्लाइड इमेज जनरेशन समाप्त हो जाएगी, जोड़ी गई html फ्रैगमेंट सम्मिलित होगी और नई इमेज पिछले के ऊपर शुरू होगी।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | आउटपुट ऑब्जेक्ट। |
| shape | [IShape](../../com.aspose.slides/ishape) | आखिरी रेंडर की गई shape। |