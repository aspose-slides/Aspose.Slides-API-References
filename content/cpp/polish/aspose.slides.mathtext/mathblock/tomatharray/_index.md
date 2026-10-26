---
title: ToMathArray()
second_title: Aspose.Slides dla C++ – referencja API
description: Umieszcza elementy potomne w pionowej tablicy
type: docs
weight: 235
url: /pl/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() metoda


Umieszcza elementy potomne w pionowej tablicy

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
```


### Wartość zwracana

Nowa instancja typu [IMathArray](../../imatharray/)
## Uwagi



Przykład: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathArray](../../imatharray/)
* Klasa [MathBlock](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)