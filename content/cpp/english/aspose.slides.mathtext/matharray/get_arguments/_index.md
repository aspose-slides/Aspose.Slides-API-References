---
title: get_Arguments()
second_title: Aspose.Slides for C++ API Reference
description: The set of items of the array
type: docs
weight: 1
url: /aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() method


The set of items of the array

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
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
* Class [MathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)