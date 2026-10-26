---
title: get_Degree()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Argument stopnia
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/imathradical/get_degree/
---
## IMathRadical::get_Degree() metoda

Argument stopnia

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Degree()=0
```

## Uwagi

Przykład:
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // pierwiastek sześcienny
auto degreeElem = radical->get_Degree();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathRadical](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)