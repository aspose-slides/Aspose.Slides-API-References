---
title: MathPortion()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بتهيئة نسخة جديدة من الفئة MathPortion.
type: docs
weight: 14
url: /ar/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() منشئ


يقوم بتهيئة نسخة جديدة من الفئة [MathPortion](../).

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## ملاحظات


مثال: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## انظر أيضًا

* الفئة [MathPortion](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)