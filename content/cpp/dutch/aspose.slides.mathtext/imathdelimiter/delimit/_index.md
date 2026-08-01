---
title: Delimit()
second_title: Aspose.Slides voor C++ API-referentie
description: Begrenst argumenten met het opgegeven scheidingsteken
type: docs
weight: 144
url: /nl/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) methode

Begrenst argumenten met het opgegeven scheidingsteken

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separatorCharacter | char16_t | scheidingsteken |

### Retourwaarde

Dit object na het toepassen van het scheidingsteken
## Opmerkingen

Voorbeeld:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathDelimiter](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)