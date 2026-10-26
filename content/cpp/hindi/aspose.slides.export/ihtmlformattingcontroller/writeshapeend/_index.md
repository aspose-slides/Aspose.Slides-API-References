---
title: WriteShapeEnd()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: आकार के रेंडरिंग से पहले कॉल किया जाता है। प्रत्येक आकार के लिए एक बार कॉल किया जाता है। यदि यह फ़ंक्शन जनरेटर में कुछ भी लिखता है, तो वर्तमान स्लाइड इमेज जेनरेशन समाप्त हो जाएगी, जोड़ा गया HTML फ्रैगमेंट सम्मिलित किया जाएगा और नई इमेज पिछले के ऊपर शुरू की जाएगी।
type: docs
weight: 66
url: /hi/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---
## IHtmlFormattingController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) विधि

आकार के रेंडरिंग से पहले कॉल किया जाता है। प्रत्येक आकार के लिए एक बार कॉल किया जाता है। यदि यह फ़ंक्शन जनरेटर में कुछ भी लिखता है, तो वर्तमान स्लाइड इमेज जनरेशन समाप्त हो जाएगी, जोड़ा गया HTML फ्रैगमेंट डाल दिया जाएगा और नई इमेज पिछले के ऊपर शुरू की जाएगी।

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | आउटपुट ऑब्जेक्ट। |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) जो अंतिम रूप से रेंडर किया गया है। |

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IHtmlGenerator](../../ihtmlgenerator/)
* क्लास [IShape](../../../aspose.slides/ishape/)
* क्लास [IHtmlFormattingController](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)