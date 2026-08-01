---
title: Enclose()
second_title: Aspose.Slides voor C++ API Referentie
description: Omsluit kindelementen van dit blok met opgegeven tekens, zoals haakjes of andere tekens als omlijning
type: docs
weight: 222
url: /nl/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) methode

Omsluit kindelementen van dit blok met opgegeven tekens, zoals haakjes of andere tekens als omlijning

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginteken (meestal linker haakje) |
| endingCharacter | char16_t | Eindteken (meestal rechter haakje) |

### Retourwaarde

Het wiskundige element van type [IMathDelimiter](../../imathdelimiter/) dat opgegeven tekens als omlijning bevat

## Opmerkingen

Voorbeeld: 
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) methode

Omsluit kindelementen van dit blok met opgegeven tekens, zoals haakjes of andere tekens als omlijning en scheidt ze met een scheidingsteken

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginteken (meestal linker haakje) |
| endingCharacter | char16_t | Eindteken (meestal rechter haakje) |
| separatorCharacter | char16_t | Scheidingsteken |

### Retourwaarde

Het wiskundige element van type [IMathDelimiter](../../imathdelimiter/) dat opgegeven tekens als omlijning en scheidingsteken bevat

## Opmerkingen

Voorbeeld: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathDelimiter](../../imathdelimiter/)
* Klasse [MathBlock](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)