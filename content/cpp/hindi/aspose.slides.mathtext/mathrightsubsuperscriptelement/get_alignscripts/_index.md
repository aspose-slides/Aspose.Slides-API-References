---
title: get_AlignScripts()
second_title: Aspose.Slides for C++ API संदर्भ
description: सबस्क्रिप्ट/सुपरस्क्रिप्ट की संरेखण को निर्दिष्ट करता है। जब true हो, सबस्क्रिप्ट और सुपरस्क्रिप्ट एक-दूसरे के सापेक्ष क्षैतिज रूप से संरेखित होते हैं। जब false हो, वे बेस के आकार के अनुसार कर्न किए जाते हैं। डिफ़ॉल्ट मान false है।
type: docs
weight: 27
url: /hi/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_alignscripts/
---
## MathRightSubSuperscriptElement::get_AlignScripts() मेथड

सबस्क्रिप्ट/सुपरस्क्रिप्ट की संरेखण को निर्दिष्ट करता है। जब true हो, सबस्क्रिप्ट और सुपरस्क्रिप्ट एक-दूसरे के सापेक्ष क्षैतिज रूप से संरेखित होते हैं। जब false हो, वे बेस के आकार के अनुसार कर्न किए जाते हैं। डिफ़ॉल्ट मान false है।

```cpp
bool Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_AlignScripts() override
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

* क्लास [MathRightSubSuperscriptElement](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)