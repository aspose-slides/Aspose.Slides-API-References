---
title: get_Subscript()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Określa argument indeksu podrzędnego, który na przykład w przypadku całki ustawia dolną granicę
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/mathnaryoperator/get_subscript/
---
## MathNaryOperator::get_Subscript() metoda

Określa argument indeksu podrzędnego, który na przykład w przypadku całki ustawia dolną granicę

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Subscript() override
```

## Uwagi

Przykład:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)