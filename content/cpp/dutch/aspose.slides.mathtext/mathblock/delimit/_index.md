---
title: Delimit()
second_title: Aspose.Slides voor C++ API-referentie
description: Delimiteert onderliggende elementen met scheidingsteken (zonder de haakjes)
type: docs
weight: 209
url: /nl/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) methode

Delimiteert onderliggende elementen met scheidingsteken (zonder de haakjes)

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separatorCharacter | char16_t | Scheidingsteken |

### Retourwaarde

Het wiskunde element van type [IMathDelimiter](../../imathdelimiter/)

## Opmerkingen

Voorbeeld:
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathDelimiter](../../imathdelimiter/)
* Klasse [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)