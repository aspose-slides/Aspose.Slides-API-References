---
title: Remove()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung.
type: docs
weight: 131
url: /de/aspose.slides.mathtext/mathblock/remove/
---
## MathBlock::Remove(System::SharedPtr\<IMathElement\>) Methode


Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung.

```cpp
bool Aspose::Slides::MathText::MathBlock::Remove(System::SharedPtr<IMathElement> item) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Das Objekt, das aus der Sammlung entfernt werden soll. |

### Rückgabewert

true, wenn *item* erfolgreich aus der Sammlung entfernt wurde; andernfalls false. Diese Methode gibt ebenfalls false zurück, wenn *item* im ursprünglichen Sammlung nicht gefunden wird.
## Bemerkungen



Beispiel: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->Remove(plusElement);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)