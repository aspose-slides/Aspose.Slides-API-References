---
title: get_Degree()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Argument stopnia
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/mathradical/get_degree/
---
## MathRadical::get_Degree() metoda


Argument stopnia

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Degree() override
```

## Uwagi


Przykład: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto degreeElem = radical->get_Degree();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathRadical](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)