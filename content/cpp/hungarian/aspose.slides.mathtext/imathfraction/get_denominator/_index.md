---
title: get_Denominator()
second_title: Aspose.Slides a C++ API referenciája
description: Nevező
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/imathfraction/get_denominator/
---
## IMathFraction::get_Denominator() metódus

Denominátor

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Denominator()=0
```

## Megjegyzések

Példa:
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto denominator = mathFraction->get_Denominator();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathFraction](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)