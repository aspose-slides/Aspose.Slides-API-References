---
title: get_Arguments()
second_title: Aspose.Slides C++ API referencia
description: A tömb elemeinek halmaza
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() metódus

A tömb elemeinek halmaza

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
```

## Megjegyzés


Példa: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElementCollection](../../imathelementcollection/)
* Osztály [IMathArray](../)
* Névtér [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)