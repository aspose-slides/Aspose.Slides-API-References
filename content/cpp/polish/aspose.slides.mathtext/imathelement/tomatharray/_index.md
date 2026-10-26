---
title: ToMathArray()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Umieszcza w pionowej tablicy
type: docs
weight: 183
url: /pl/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() metoda


Umieszcza w pionowej tablicy

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
```


### Wartość zwracana

Nowa instancja typu [IMathArray](../../imatharray/)
## Uwagi



Przykład: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathArray](../../imatharray/)
* Klasa [IMathElement](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)