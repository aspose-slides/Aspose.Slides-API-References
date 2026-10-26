---
title: get_SpellCheck()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: पाठ भाग के लिए यह बताने वाला मान प्राप्त करता है कि वर्तनी जाँच सक्षम है या नहीं। जब इस प्रॉपर्टी को false सेट किया जाता है, तो पाठ तत्वों के लिए वर्तनी जाँच दमन हो जाती है। जब इसे true सेट किया जाता है, तो वर्तनी जाँच की अनुमति मिलती है। डिफ़ॉल्ट मान false है।
type: docs
weight: 599
url: /hi/aspose.slides/baseportionformat/get_spellcheck/
---
## BasePortionFormat::get_SpellCheck() विधि


BasePortionFormat::get_SpellCheck() मेथड के लिए पाठ भाग में वर्तनी जांच सक्षम है या नहीं, इसका संकेत देने वाले मान को प्राप्त करता है। जब इस प्रॉपर्टी को false सेट किया जाता है, तो पाठ तत्वों के लिए वर्तनी जांच दमन कर दी जाती है। जब इसे true सेट किया जाता है, तो वर्तनी जांच अनुमति प्राप्त करती है। डिफॉल्ट मान **false** है।

```cpp
bool Aspose::Slides::BasePortionFormat::get_SpellCheck() override
```

## टिप्पणियाँ


अगला उदाहरण प्रस्तुति सहेजने से पहले SpellCheck फ़्लैग को सक्षम करने को दर्शाता है: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
portion->get_PortionFormat()->set_SpellCheck(true);
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* वर्ग [BasePortionFormat](../)
* नामस्थान [Aspose::Slides](../../)
* पुस्तकालय [Aspose.Slides](../../../)