---
title: get_SpellCheck()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: टेक्स्ट भाग के लिए वर्तनी जाँच सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। जब इस प्रॉपर्टी को false पर सेट किया जाता है, तो टेक्स्ट तत्वों के लिए वर्तनी जाँच दबा दी जाती है। जब इसे true पर सेट किया जाता है, तो वर्तनी जाँच की अनुमति दी जाती है। डिफ़ॉल्ट मान false है।
type: docs
weight: 599
url: /hi/aspose.slides/ibaseportionformat/get_spellcheck/
---
## IBasePortionFormat::get_SpellCheck() विधि

टेक्स्ट भाग के लिए वर्तनी जाँच सक्षम है या नहीं, यह दर्शाने वाला एक मान प्राप्त करता है। जब इस प्रॉपर्टी को false पर सेट किया जाता है, तो टेक्स्ट तत्वों के लिए वर्तनी जाँच दबा दी जाती है। जब इसे true पर सेट किया जाता है, तो वर्तनी जाँच की अनुमति दी जाती है। डिफ़ॉल्ट मान **false** है।

```cpp
virtual bool Aspose::Slides::IBasePortionFormat::get_SpellCheck()=0
```
## टिप्पणी

अगला उदाहरण प्रस्तुति को सहेजने से पहले SpellCheck फ़्लैग को सक्षम करने को दर्शाता है: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// पहली स्लाइड पर पहले आकार के भीतर टेक्स्ट के पहले हिस्से तक पहुँचें
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// इस टेक्स्ट हिस्से के लिए वर्तनी जाँच सक्षम करें
portion->get_PortionFormat()->set_SpellCheck(true);
// संशोधित प्रस्तुति सहेजें
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* क्लास [IBasePortionFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)