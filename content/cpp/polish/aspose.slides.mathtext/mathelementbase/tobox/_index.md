---
title: ToBox()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Umieszcza ten element w niewidzialnym boksie (logiczna grupacja), który służy do grupowania składników równania lub innego wystąpienia tekstu matematycznego. Obiekt w boksie może (na przykład) pełnić rolę emulatora operatora z punktem wyrównania lub bez niego, służyć jako punkt łamania linii lub być grupowany w taki sposób, aby nie dopuszczać do łamania linii wewnątrz.
type: docs
weight: 261
url: /pl/aspose.slides.mathtext/mathelementbase/tobox/
---
## MathElementBase::ToBox() metoda


Umieszcza ten element w niewidzialnym boxie (grupowaniu logicznym), który służy do grupowania składników równania lub innego wystąpienia tekstu matematycznego. Obiekt w boxie może (na przykład) działać jako emulator operatora z punktem wyrównania lub bez niego, pełnić rolę punktu przerwania linii lub być grupowany w taki sposób, aby nie zezwalać na przerwy wierszy wewnątrz.

```cpp
System::SharedPtr<IMathBox> Aspose::Slides::MathText::MathElementBase::ToBox() override
```


### Wartość zwracana

Logiczny box z umieszczonym wewnątrz tym elementem
## Uwagi



Przykład: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBox](../../imathbox/)
* Klasa [MathElementBase](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)