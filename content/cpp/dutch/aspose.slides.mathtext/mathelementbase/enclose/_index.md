---
title: Enclose()
second_title: Aspose.Slides voor C++ API-referentie
description: Omsluit een wiskundig element in haakjes
type: docs
weight: 27
url: /nl/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() methode

Omvat een wiskundig element in haakjes

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```

### Retourwaarde

Het wiskundige element van type [IMathDelimiter](../../imathdelimiter/) dat de haakjes bevat
## Opmerkingen



Voorbeeld: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) methode

Omvat een wiskundig element in opgegeven tekens, zoals haakjes of andere tekens als omkadering

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| beginningCharacter | char16_t | Begin teken (meestal linker haak) |
| endingCharacter | char16_t | Eind teken (meestal rechter haak) |

### Retourwaarde

Het wiskundige element van type [IMathDelimiter](../../imathdelimiter/) dat de opgegeven tekens als omkadering bevat
## Opmerkingen



Voorbeeld: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathDelimiter](../../imathdelimiter/)
* Klasse [MathElementBase](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)