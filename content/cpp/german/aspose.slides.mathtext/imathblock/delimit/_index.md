---
title: Delimit()
second_title: Aspose.Slides für C++ API-Referenz
description: Begrenzt alle Kindelemente mit dem Trennzeichen (ohne die Klammern)
type: docs
weight: 1
url: /de/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) Methode

Begrenzt alle Kindelemente mit dem Trennzeichen (ohne die Klammern)

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separatorCharacter | char16_t | Zeichen, das als Trennzeichen verwendet wird |

### Rückgabewert

Instanz von [IMathDelimiter](../../imathdelimiter/) Element

## Anmerkungen



Beispiel: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathDelimiter](../../imathdelimiter/)
* Klasse [IMathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)