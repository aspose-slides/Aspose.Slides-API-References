---
title: set_NoBreak()
second_title: Aspose.Slides for C++ API संदर्भ
description: "नो ब्रेक। यह प्रॉपर्टी ऑब्जेक्ट बॉक्स पर \"अविभाज्य\" प्रॉपर्टी को निर्दिष्ट करती है। जब true हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता। यह उन ऑपरेटर इम्यूलेटरों के लिए महत्वपूर्ण हो सकता है जिनमें एक से अधिक बाइनरी ऑपरेटर होते हैं। जब यह तत्व निर्दिष्ट नहीं किया जाता, तो बॉक्स के अंदर ब्रेक हो सकते हैं। डिफ़ॉल्ट: true"
type: docs
weight: 53
url: /hi/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(bool) method

कोई ब्रेक नहीं। यह प्रॉपर्टी ऑब्जेक्ट बॉक्स पर \"अविभाज्य\" प्रॉपर्टी को निर्दिष्ट करती है। जब true हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता। यह उन ऑपरेटर इम्यूलेटरों के लिए महत्वपूर्ण हो सकता है जिनमें एक से अधिक बाइनरी ऑपरेटर होते हैं। जब यह तत्व निर्दिष्ट नहीं किया जाता है, तो बॉक्स के भीतर ब्रेक हो सकते हैं। डिफ़ॉल्ट: true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## संबंधित देखें

* क्लास [IMathBox](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)