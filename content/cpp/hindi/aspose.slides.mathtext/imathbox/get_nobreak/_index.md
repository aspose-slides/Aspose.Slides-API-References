---
title: get_NoBreak()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: "कोई ब्रेक नहीं। यह प्रॉपर्टी ऑब्जेक्ट बॉक्स पर \"unbreakable\" प्रॉपर्टी को निर्दिष्ट करती है। जब true हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता। यह उन ऑपरेटर एमुलेटरों के लिए महत्वपूर्ण हो सकता है जो एक से अधिक बाइनरी ऑपरेटर से बने होते हैं। जब इस तत्व को निर्दिष्ट नहीं किया जाता है, तो बॉक्स के भीतर ब्रेक हो सकते हैं। Default: true"
type: docs
weight: 40
url: /hi/aspose.slides.mathtext/imathbox/get_nobreak/
---
## IMathBox::get_NoBreak() विधि

कोई ब्रेक नहीं। यह प्रॉपर्टी ऑब्जेक्ट बॉक्स पर "unbreakable" प्रॉपर्टी को निर्दिष्ट करती है। जब true हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता। यह उन ऑपरेटर एमुलेटरों के लिए महत्वपूर्ण हो सकता है जो एक से अधिक बाइनरी ऑपरेटर से मिलकर बनते हैं। जब इस तत्व को निर्दिष्ट नहीं किया जाता है, तो बॉक्स के अंदर ब्रेक हो सकते हैं। डिफ़ॉल्ट: true

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_NoBreak()=0
```

## टिप्पणी

उदाहरण: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## संबंधित देखें

* क्लास [IMathBox](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)