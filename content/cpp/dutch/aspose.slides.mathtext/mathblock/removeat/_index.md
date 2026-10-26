---
title: RemoveAt()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert het element op de opgegeven index van de collectie.
type: docs
weight: 170
url: /nl/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock::RemoveAt(int32_t) methode


Verwijdert het element op de opgegeven index van de collectie.

```cpp
void Aspose::Slides::MathText::MathBlock::RemoveAt(int32_t index) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index van het element dat verwijderd moet worden. |
## Opmerkingen



Voorbeeld: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->RemoveAt(2);
```

## Zie ook

* Klasse [MathBlock](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)