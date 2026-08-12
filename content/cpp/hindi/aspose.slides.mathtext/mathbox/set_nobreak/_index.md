---
title: set_NoBreak()
second_title: Aspose.Slides for C++ API संदर्भ
description: "No break यह प्रॉपर्टी ऑब्जेक्ट बॉक्स पर \"unbreakable\" प्रॉपर्टी को निर्दिष्ट करती है। जब true हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता। यह एक से अधिक बाइनरी ऑपरेटर वाले ऑपरेटर इम्यूलेटर के लिए महत्वपूर्ण हो सकता है। जब यह तत्व निर्दिष्ट नहीं किया जाता, तो बॉक्स के अंदर ब्रेक हो सकते हैं। डिफ़ॉल्ट: true"
type: docs
weight: 53
url: /hi/aspose.slides.mathtext/mathbox/set_nobreak/
---
## MathBox::set_NoBreak(bool) विधि


No break यह प्रॉपर्टी ऑब्जेक्ट बॉक्स पर \"unbreakable\" प्रॉपर्टी को निर्धारित करती है। जब true हो, बॉक्स के अंदर कोई लाइन ब्रेक नहीं हो सकता। यह एक से अधिक बाइनरी ऑपरेटर वाले ऑपरेटर इम्यूलेटर के लिए महत्वपूर्ण हो सकता है। जब यह तत्व निर्दिष्ट नहीं किया जाता, तो बॉक्स के अंदर ब्रेक हो सकते हैं। डिफ़ॉल्ट: true

```cpp
void Aspose::Slides::MathText::MathBox::set_NoBreak(bool value) override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## संबंधित देखें

* क्लास [MathBox](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)