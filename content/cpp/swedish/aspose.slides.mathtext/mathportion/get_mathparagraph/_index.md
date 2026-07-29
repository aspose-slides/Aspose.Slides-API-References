---
title: get_MathParagraph()
second_title: Aspose.Slides för C++ API-referens
description: Matematisk stycke
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/mathportion/get_mathparagraph/
---
## MathPortion::get_MathParagraph() method


Matematisk stycke

```cpp
System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::MathPortion::get_MathParagraph() override
```

## Anmärkningar


Exempel: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x+y")));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathParagraph](../../imathparagraph/)
* Klass [MathPortion](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)