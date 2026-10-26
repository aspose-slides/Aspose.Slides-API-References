---
title: WriteShapeEnd()
second_title: Aspose.Slides के लिए C++ API रेफरेंस
description: शेप के रेंडरिंग से पहले कॉल किया जाता है। प्रत्येक शेप के लिए एक बार कॉल किया जाता है। यदि यह फ़ंक्शन जेनरेटर में कुछ लिखता है, तो वर्तमान स्लाइड इमेज जेनरेशन समाप्त हो जाएगी, जोड़ा गया HTML फ्रैगमेंट सम्मिलित किया जाएगा और नई इमेज पिछली के ऊपर शुरू होगी।
type: docs
weight: 79
url: /hi/aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---
## EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) विधि

शेप के रेंडरिंग से पहले कॉल किया जाता है। प्रत्येक शेप के लिए एक बार कॉल किया जाता है। यदि यह फ़ंक्शन जेनरेटर में कुछ लिखता है, तो वर्तमान स्लाइड इमेज जेनरेशन समाप्त हो जाएगी, जोड़ा गया html फ्रैगमेंट सम्मिलित किया जाएगा और नई इमेज पिछली के ऊपर शुरू होगी।

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | आउटपुट ऑब्जेक्ट। |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) जो अंतिम बार रेंडर किया गया है। |

## और देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IHtmlGenerator](../../ihtmlgenerator/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [EmbedAllFontsHtmlController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)