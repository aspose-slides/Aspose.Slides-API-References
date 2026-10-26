---
title: MathPortion()
second_title: Aspose.Slides for C++ API संदर्भ
description: MathPortion वर्ग का एक नया उदाहरण आरंभ करता है।
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() निर्माता


[MathPortion](../) क्लास का एक नया उदाहरण बनाता है।

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## देखें

* क्लास [MathPortion](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)