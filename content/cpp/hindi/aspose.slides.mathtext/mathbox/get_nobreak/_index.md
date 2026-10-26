---
title: get_NoBreak()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "कोई विराम नहीं यह प्रॉपर्टी ऑब्जेक्ट बॉक्स पर \"unbreakable\" प्रॉपर्टी को निर्दिष्ट करती है। जब true हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता। यह उन ऑपरेटर एмуляटरों के लिए महत्वपूर्ण हो सकता है जो एक से अधिक बाइनरी ऑपरेटर से बने होते हैं। जब यह तत्व निर्दिष्ट नहीं किया जाता, तो बॉक्स के अंदर ब्रेक हो सकते हैं। डिफ़ॉल्ट: true"
type: docs
weight: 40
url: /hi/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() मेथड


No break यह प्रॉपर्टी ऑब्जेक्ट बॉक्स पर "unbreakable" प्रॉपर्टी को निर्दिष्ट करती है। जब true हो, बॉक्स के भीतर किसी भी लाइन ब्रेक की अनुमति नहीं रहती। यह उन ऑपरेटर इम्यूलेटरों के लिए महत्वपूर्ण हो सकता है जो एक से अधिक बाइनरी ऑपरेटर से बना होते हैं। जब यह तत्व निर्दिष्ट नहीं किया जाता, तो बॉक्स के अंदर ब्रेक हो सकते हैं। डिफ़ॉल्ट: true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## संबंधित

* क्लास [MathBox](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)