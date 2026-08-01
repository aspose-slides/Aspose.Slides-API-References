---
title: Enclose()
second_title: Aspose.Slides voor C++ API-referentie
description: Omvat kindelementen van dit blok in opgegeven tekens, zoals haakjes of andere, als omlijning en scheidt ze met een scheidingsteken
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) methode

Omvat kindelementen van dit blok in opgegeven tekens, zoals haakjes of andere, als omlijning en scheidt ze met een scheidingsteken

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| beginningCharacter | char16_t | Begin teken (meestal linkerhaak) |
| endingCharacter | char16_t | Eind teken (meestal rechterhaak) |
| separatorCharacter | char16_t | Scheidingsteken |

### Retourwaarde

Het wiskunde-element van type [IMathDelimiter](../../imathdelimiter/) dat de opgegeven tekens als omlijning en scheidingsteken bevat

## Opmerkingen



Voorbeeld: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathDelimiter](../../imathdelimiter/)
* Klasse [IMathBlock](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)