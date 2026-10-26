---
title: get_Arguments()
second_title: Aspose.Slides für C++ API-Referenz
description: Die Menge der Elemente des Arrays
type: docs
weight: 1
url: /de/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() Methode


Die Menge der Elemente des Arrays

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
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
* Klasse [MathArray](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)