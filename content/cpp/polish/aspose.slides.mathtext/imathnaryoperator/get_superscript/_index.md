---
title: get_Superscript()
second_title: Referencja API Aspose.Slides dla C++
description: Określa argument superskriptu, który na przykład w przypadku całki ustawia górny limit
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/imathnaryoperator/get_superscript/
---
## IMMathNaryOperator::get_Superscript() metoda


Określa argument superskriptu, który na przykład w przypadku całki ustawia górny limit

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Superscript()=0
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
* Klasa [IMathNaryOperator](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)