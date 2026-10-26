---
title: ToMathArray()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Umieszcza w pionowej tablicy
type: docs
weight: 170
url: /pl/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() metoda


Umieszcza w pionowej tablicy

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
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
* Klasa [MathElementBase](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)