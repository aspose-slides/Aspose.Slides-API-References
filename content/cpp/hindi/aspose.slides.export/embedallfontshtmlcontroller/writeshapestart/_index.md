---
title: WriteShapeStart()
second_title: Aspose.Slides for C++ API संदर्भ
description: शेप के रेंडरिंग से पहले बुलाया जाता है। प्रत्येक शेप के लिए एक बार बुलाया जाता है। यदि यह फ़ंक्शन जेनरेटर में कुछ लिखता है, तो वर्तमान स्लाइड इमेज निर्माण समाप्त हो जाएगा, जोड़ा गया HTML फ्रैगमेंट सम्मिलित होगा और नई इमेज पिछले के ऊपर शुरू होगी।
type: docs
weight: 66
url: /hi/aspose.slides.export/embedallfontshtmlcontroller/writeshapestart/
---
## EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) विधि

शेप के रेंडरिंग से पहले बुलाया जाता है। प्रत्येक शेप के लिए एक बार बुलाया जाता है। यदि यह फ़ंक्शन जेनरेटर में कुछ लिखता है, तो वर्तमान स्लाइड इमेज जनरेशन समाप्त हो जाएगी, जोड़ा गया HTML फ्रैगमेंट सम्मिलित होगा और नई इमेज पिछले के ऊपर शुरू होगी।

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | आउटपुट ऑब्जेक्ट। |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) जो रेंडर होने वाला है। |

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IHtmlGenerator](../../ihtmlgenerator/)
* क्लास [IShape](../../../aspose.slides/ishape/)
* क्लास [EmbedAllFontsHtmlController](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)