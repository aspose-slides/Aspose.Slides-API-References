---
title: set_SpellCheck()
second_title: Aspose.Slides for C++ API संदर्भ
description: टेक्स्ट भाग के लिए स्पेल चेकिंग सक्षम है या नहीं, इसे दर्शाने वाला मान सेट करता है। जब यह प्रॉपर्टी false पर सेट होती है, तो टेक्स्ट तत्वों के लिए वर्तनी जाँच दबा दी जाती है। जब यह true पर सेट होती है, तो स्पेल चेकिंग की अनुमति होती है। डिफ़ॉल्ट मान false है।
type: docs
weight: 612
url: /hi/aspose.slides/baseportionformat/set_spellcheck/
---
## BasePortionFormat::set_SpellCheck(bool) मेथड

टेक्स्ट भाग के लिए स्पेल चेकिंग सक्षम है या नहीं, इसे दर्शाने वाला मान सेट करता है। जब यह प्रॉपर्टी false पर सेट होती है, तो टेक्स्ट तत्वों के लिए वर्तनी जाँच दबा दी जाती है। जब यह true पर सेट होती है, तो स्पेल चेकिंग की अनुमति होती है। डिफ़ॉल्ट मान **false** है।

```cpp
void Aspose::Slides::BasePortionFormat::set_SpellCheck(bool value) override
```

## टिप्पणी

अगला उदाहरण प्रस्तुतिकरण को सहेजने से पहले SpellCheck फ्लैग को सक्षम करने का प्रदर्शन करता है:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// पहले स्लाइड पर पहली शैप के अंदर प्रथम टेक्स्ट भाग तक पहुँचें
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// इस टेक्स्ट भाग के लिए स्पेल चेकिंग सक्षम करें
portion->get_PortionFormat()->set_SpellCheck(true);
// संशोधित प्रस्तुति को सहेजें
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## देखें

* क्लास [BasePortionFormat](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)