---
title: set_AlignScripts()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: उपस्क्रिप्ट/उपरस्क्रिप्ट की संरेखण को निर्दिष्ट करता है। जब true हो, तो उपस्क्रिप्ट और उपरस्क्रिप्ट क्षैतिज रूप से एक-दूसरे के साथ संरेखित होते हैं। जब false हो, तो वे आधार के आकार के अनुसार कर्न किए जाते हैं। डिफ़ॉल्ट मान false है।
type: docs
weight: 53
url: /hi/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) मेथड

उपस्क्रिप्ट/उपरस्क्रिप्ट की संरेखण को निर्दिष्ट करता है। जब true हो, तो उपस्क्रिप्ट और उपरस्क्रिप्ट क्षैतिज रूप से एक-दूसरे के साथ संरेखित होते हैं। जब false हो, तो वे आधार के आकार के अनुसार कर्न किए जाते हैं। डिफ़ॉल्ट मान false है।

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
```

## टिप्पणी

उदाहरण:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## संबंधित देखें

* क्लास [IMathRightSubSuperscriptElement](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)