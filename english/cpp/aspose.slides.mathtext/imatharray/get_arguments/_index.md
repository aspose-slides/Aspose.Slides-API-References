---
title: get_Arguments()
second_title: Aspose.Slides for C++ API Reference
description: The set of items of the array
type: docs
weight: 1
url: /cpp/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() method


The set of items of the array

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
```

## Remarks


Example: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElementCollection](../../imathelementcollection/)
* Class [IMathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
