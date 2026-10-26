---
title: Delimit()
second_title: Aspose.Slides für C++ API-Referenz
description: Begrenzt Kindelemente mit Trennzeichen (ohne die Klammern)
type: docs
weight: 209
url: /de/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) Methode


Begrenzt Kindelemente mit Trennzeichen (ohne die Klammern)

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separatorCharacter | char16_t | Trennzeichen |

### Rückgabewert

Das mathematische Element des Typs [IMathDelimiter](../../imathdelimiter/)
## Anmerkungen



Beispiel: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathDelimiter](../../imathdelimiter/)
* Klasse [MathBlock](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)