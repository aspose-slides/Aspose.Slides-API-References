---
title: get_Base()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Argument bazowy
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathradical/get_base/
---
## IMathRadical::get_Base() metoda

Argument bazowy

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Base()=0
```

## Uwagi

## Przykład:
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // pierwiastek sześcienny
auto baseElem = radical->get_Base();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathRadical](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)