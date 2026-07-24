---
title: RemoveAt()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt das Element am angegebenen Index der Sammlung.
type: docs
weight: 170
url: /de/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock::RemoveAt(int32_t) Methode


Entfernt das Element am angegebenen Index der Sammlung.

```cpp
void Aspose::Slides::MathText::MathBlock::RemoveAt(int32_t index) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index des zu entfernenden Elements. |
## Hinweise



Beispiel: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->RemoveAt(2);
```

## Siehe auch

* Klasse [MathBlock](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)