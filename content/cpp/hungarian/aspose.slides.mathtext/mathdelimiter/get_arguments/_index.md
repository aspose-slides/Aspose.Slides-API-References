---
title: get_Arguments()
second_title: Aspose.Slides for C++ API referenciája
description: Egy vagy több matematikai elem, amelyet elválasztó karakterek választanak el
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/mathdelimiter/get_arguments/
---
## MathDelimiter::get_Arguments() metódus


Egy vagy több matematikai elem, amelyet elválasztó karakterek választanak el

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathDelimiter::get_Arguments() override
```

## Megjegyzések


Példa: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElementCollection](../../imathelementcollection/)
* Osztály [MathDelimiter](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)