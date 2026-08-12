---
title: set_AlignScripts()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सबस्क्रिप्ट/सुपरस्क्रिप्ट की अभिचलन को निर्दिष्ट करता है। जब true हो, तो सबस्क्रिप्ट और सुपरस्क्रिप्ट एक दूसरे के सापेक्ष क्षैतिज रूप से संरेखित होते हैं। जब false हो, तो वे बेस के आकार के अनुसार कर्न्ड होते हैं। डिफ़ॉल्ट मान false है।
type: docs
weight: 40
url: /hi/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) विधि

सबस्क्रिप्ट/सुपरस्क्रिप्ट की अभिचलन को निर्दिष्ट करता है। जब true हो, तो सबस्क्रिप्ट और सुपरस्क्रिप्ट एक दूसरे के सापेक्ष क्षैतिज रूप से संरेखित होते हैं। जब false हो, तो वे बेस के आकार के अनुसार कर्न्ड होते हैं। डिफ़ॉल्ट मान false है।

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
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