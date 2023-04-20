---
title: set_BaseJustification()
second_title: Aspose.Slides for C++ API Reference
description: "Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. Default value: Center"
type: docs
weight: 27
url: /cpp/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) method


Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. Default value: Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
```

## Remarks


Example: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## See Also

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Class [IMathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)