---
title: get_Arguments()
second_title: Aspose.Slides C++ API referenciája
description: A tömb elemeinek halmaza
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() metódus


A tömb elemeinek halmaza

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
```

## Megjegyzések


Példa: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElementCollection](../../imathelementcollection/)
* Osztály [MathArray](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)