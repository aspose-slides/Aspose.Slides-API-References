---
title: get_BaseJustification()
second_title: Aspose.Slides for C++ API Reference
description: "Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. Default value: Center"
type: docs
weight: 14
url: /aspose.slides.mathtext/imatharray/get_basejustification/
---
## IMathArray::get_BaseJustification() method


Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. Default value: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathArray::get_BaseJustification()=0
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