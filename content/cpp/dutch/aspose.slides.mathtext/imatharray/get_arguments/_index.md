---
title: get_Arguments()
second_title: Aspose.Slides voor C++ API-referentie
description: De set van items van de array
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() methode


De set van items van de array

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
```

## Opmerkingen


Voorbeeld: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElementCollection](../../imathelementcollection/)
* Klasse [IMathArray](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)