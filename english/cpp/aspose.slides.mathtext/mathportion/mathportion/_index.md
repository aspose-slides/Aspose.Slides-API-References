---
title: MathPortion()
second_title: Aspose.Slides for C++ API Reference
description: Initializes a new instance of the MathPortion class.
type: docs
weight: 14
url: /cpp/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() constructor


Initializes a new instance of the [MathPortion](../) class.

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## Remarks


Example: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## See Also

* Class [MathPortion](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
