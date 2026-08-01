---
title: IndexOf()
second_title: Aspose.Slides voor C++ API Referentie
description: Bepaalt de index van een specifiek wiskundig element in de collectie.
type: docs
weight: 144
url: /nl/aspose.slides.mathtext/mathblock/indexof/
---
## MathBlock::IndexOf(System::SharedPtr\<IMathElement\>) methode

Bepaalt de index van een specifiek wiskundig element in de collectie.

```cpp
int32_t Aspose::Slides::MathText::MathBlock::IndexOf(System::SharedPtr<IMathElement> item) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Het element om te vinden in de collectie. |

### Retourwaarde

De index van *item* als deze in de collectie wordt gevonden; anders -1.
## Opmerkingen


Voorbeeld: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
int32_t index = mathBlock->IndexOf(plusElement);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathBlock](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)