---
title: Insert()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt ein MathElement in die Sammlung an dem angegebenen Index ein.
type: docs
weight: 157
url: /de/aspose.slides.mathtext/mathblock/insert/
---
## MathBlock::Insert(int32_t, System::SharedPtr\<IMathElement\>) Methode

Fügt ein MathElement in die Sammlung an dem angegebenen Index ein.

```cpp
void Aspose::Slides::MathText::MathBlock::Insert(int32_t index, System::SharedPtr<IMathElement> item) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem MathElement eingefügt werden soll. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Das einzufügende MathElement. |

## Anmerkungen



Beispiel: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathBlock](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)