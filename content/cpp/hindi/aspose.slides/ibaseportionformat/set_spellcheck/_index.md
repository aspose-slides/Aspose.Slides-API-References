---
title: set_SpellCheck()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: टेक्स्ट भाग के लिए वर्तनी जाँच सक्षम है या नहीं, यह दर्शाने वाला मान सेट करता है। जब इस प्रॉपर्टी को false पर सेट किया जाता है, तो टेक्स्ट तत्वों के लिए वर्तनी जाँच दबी रहती है। जब इसे true पर सेट किया जाता है, तो वर्तनी जाँच की अनुमति होती है। डिफ़ॉल्ट मान false है।
type: docs
weight: 612
url: /hi/aspose.slides/ibaseportionformat/set_spellcheck/
---
## IBasePortionFormat::set_SpellCheck(bool) विधि

टेक्स्ट भाग के लिए वर्तनी जांच सक्षम है या नहीं, यह दर्शाने वाला मान सेट करता है। जब इस प्रॉपर्टी को false पर सेट किया जाता है, तो टेक्स्ट तत्वों के लिए वर्तनी जांच दबा दी जाती है। जब इसे true पर सेट किया जाता है, तो वर्तनी जांच की अनुमति होती है। डिफ़ॉल्ट मान **false** है।

```cpp
virtual void Aspose::Slides::IBasePortionFormat::set_SpellCheck(bool value)=0
```

## टिप्पणी


अगला उदाहरण प्रस्तुति को सहेजने से पहले SpellCheck फ़्लैग को सक्षम करने को दर्शाता है: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// पहली स्लाइड पर पहले आकार के भीतर टेक्स्ट के पहले भाग तक पहुँचें
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// इस टेक्स्ट भाग के लिए वर्तनी जाँच सक्षम करें
portion->get_PortionFormat()->set_SpellCheck(true);
// परिवर्तित प्रस्तुति को सहेजें
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* वर्ग [IBasePortionFormat](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)