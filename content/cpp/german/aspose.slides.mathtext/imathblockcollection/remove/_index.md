---
title: Remove()
second_title: Aspose.Slides für C++ API Referenz
description: Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung/>.
type: docs
weight: 40
url: /de/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove(System::SharedPtr\<IMathBlock\>) Methode

Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung/>.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Das Objekt, das aus der Sammlung entfernt werden soll. |

### Rückgabewert

true, wenn *item* erfolgreich aus der Sammlung entfernt wurde; andernfalls false. Diese Methode liefert ebenfalls false, wenn *item* in der ursprünglichen Sammlung nicht gefunden wird/>.

## Anmerkungen

Beispiel:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBlock](../../imathblock/)
* Klasse [IMathBlockCollection](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)