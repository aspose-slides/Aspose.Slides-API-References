---
title: MathPortion()
second_title: Aspose.Slides for C++ API Referansı
description: MathPortion sınıfının yeni bir örneğini başlatır.
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() yapıcı

[MathPortion](../) sınıfının yeni bir örneğini başlatır.

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## Açıklamalar

Örnek:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## İlgili

* Sınıf [MathPortion](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)