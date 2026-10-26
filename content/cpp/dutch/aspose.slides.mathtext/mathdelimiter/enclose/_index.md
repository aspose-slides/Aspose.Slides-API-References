---
title: Enclose()
second_title: Aspose.Slides voor C++ API-referentie
description: Omsluit een wiskundig element in opgegeven tekens, zoals haakjes of andere tekens als kader
type: docs
weight: 170
url: /nl/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) method

Omsluit een wiskundig element in opgegeven tekens, zoals haakjes of andere tekens als kader

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginteken (meestal linker haak) |
| endingCharacter | char16_t | Eindteken (meestal rechter haak) |

### Retourwaarde

If *beginningCharacter*  and *endingCharacter*  are null, corresponding properties are assigned values only and no new object is created (returns this instance). Otherwise, returns new math element of type Delimiter which includes specified characters as framing and this instance of [MathDelimiter](../) framed inside.

## Opmerkingen

Voorbeeld: 
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathDelimiter](../../imathdelimiter/)
* Klasse [MathDelimiter](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)