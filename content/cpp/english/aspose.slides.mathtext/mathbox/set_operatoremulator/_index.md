---
title: set_OperatorEmulator()
second_title: Aspose.Slides for C++ API Reference
description: "Operator Emulator. When true, the box and its contents behave as a single operator and inherit the properties of an operator. This means, for example, that the character can serve as a point for a line break and can be aligned to other operators. Operator Emulators are often used when one or more glyphs combine to form an operator, such as '=='. Default value: false"
type: docs
weight: 27
url: /aspose.slides.mathtext/mathbox/set_operatoremulator/
---
## MathBox::set_OperatorEmulator(bool) method


Operator Emulator. When true, the box and its contents behave as a single operator and inherit the properties of an operator. This means, for example, that the character can serve as a point for a line break and can be aligned to other operators. Operator Emulators are often used when one or more glyphs combine to form an operator, such as '=='. Default value: false

```cpp
void Aspose::Slides::MathText::MathBox::set_OperatorEmulator(bool value) override
```

## Remarks


Example: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## See Also

* Class [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)