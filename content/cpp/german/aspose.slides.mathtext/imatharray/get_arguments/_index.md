---
title: get_Arguments()
second_title: Aspose.Slides für C++ API-Referenz
description: Die Menge der Elemente des Arrays
type: docs
weight: 1
url: /de/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() Methode


Die Menge der Elemente des Arrays

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
```

## Hinweise


Beispiel:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElementCollection](../../imathelementcollection/)
* Klasse [IMathArray](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)