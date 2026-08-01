---
title: Delimit()
second_title: Aspose.Slides voor C++ API-referentie
description: Delimiteert alle kindelementen met scheidingsteken (zonder de haakjes)
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) methode

Delimiteert alle kindelementen met scheidingsteken (zonder de haakjes)

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separatorCharacter | char16_t | Teken dat als scheidingsteken wordt gebruikt |

### Retourwaarde

Instantie van [IMathDelimiter](../../imathdelimiter/) element
## Opmerkingen



Voorbeeld: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathDelimiter](../../imathdelimiter/)
* Klasse [IMathBlock](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)