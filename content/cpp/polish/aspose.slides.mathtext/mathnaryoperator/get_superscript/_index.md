---
title: get_Superscript()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Określa argument superskryptowy, który na przykład w przypadku całki ustawia górną granicę
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/mathnaryoperator/get_superscript/
---
## MathNaryOperator::get_Superscript() metoda

Określa argument superskryptowy, który na przykład w przypadku całki ustawia górną granicę

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Superscript() override
```

## Uwagi

Przykład:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathNaryOperator](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)