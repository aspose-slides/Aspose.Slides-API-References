---
title: get_Arguments()
second_title: Aspose.Slides C++ API referencia
description: Egy vagy több matematikai elem, amelyet elválasztó karakterek választanak el
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/imathdelimiter/get_arguments/
---
## IMathDelimiter::get_Arguments() metódus

Egy vagy több matematikai elem, amelyet elválasztó karakterek választanak el

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathDelimiter::get_Arguments()=0
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
* Osztály [IMathDelimiter](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)