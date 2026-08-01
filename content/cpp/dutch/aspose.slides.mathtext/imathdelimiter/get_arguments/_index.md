---
title: get_Arguments()
second_title: Aspose.Slides voor C++ API-referentie
description: Een of meer wiskundige elementen gescheiden door scheidingsteken
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/imathdelimiter/get_arguments/
---
## IMathDelimiter::get_Arguments() methode

Een of meer wiskundige elementen gescheiden door scheidingsteken

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathDelimiter::get_Arguments()=0
```

## Opmerkingen

Voorbeeld: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElementCollection](../../imathelementcollection/)
* Klasse [IMathDelimiter](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)