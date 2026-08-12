---
title: WriteShapeStart()
second_title: Aspose.Slides for C++ API संदर्भ
description: शेप के रेंडरिंग से पहले कॉल किया जाता है। प्रत्येक शेप के लिए यह एक बार कॉल होता है। यदि यह फ़ंक्शन जनरेटर में कुछ लिखता है, तो वर्तमान स्लाइड इमेज जेनरेशन समाप्त हो जाएगी, जोड़ा गया HTML टुकड़ा सम्मिलित किया जाएगा और नई इमेज पिछले के ऊपर शुरू की जाएगी।
type: docs
weight: 53
url: /hi/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) विधि

शेप के रेंडरिंग से पहले कॉल किया जाता है। प्रत्येक शेप के लिए यह एक बार कॉल होता है। यदि यह फ़ंक्शन जनरेटर में कुछ लिखता है, तो वर्तमान स्लाइड इमेज जेनरेशन समाप्त हो जाएगी, जोड़ा गया HTML टुकड़ा सम्मिलित किया जाएगा और नई इमेज पिछले के ऊपर शुरू हो जाएगी।

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### आर्ग्यूमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | आउटपुट ऑब्जेक्ट। |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) जो रेंडर होने वाला है। |

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IHtmlGenerator](../../ihtmlgenerator/)
* क्लास [IShape](../../../aspose.slides/ishape/)
* क्लास [IHtmlFormattingController](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)