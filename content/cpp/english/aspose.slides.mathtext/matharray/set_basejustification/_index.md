---
title: set_BaseJustification()
second_title: Aspose.Slides for C++ API Reference
description: "Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. Default value: Center"
type: docs
weight: 27
url: /aspose.slides.mathtext/matharray/set_basejustification/
---
## MathArray::set_BaseJustification(MathVerticalAlignment) method


Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. Default value: Center

```cpp
void Aspose::Slides::MathText::MathArray::set_BaseJustification(MathVerticalAlignment value) override
```

## Remarks


Example: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## See Also

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Class [MathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)