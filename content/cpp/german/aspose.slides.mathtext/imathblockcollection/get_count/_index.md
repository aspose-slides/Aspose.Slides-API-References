---
title: get_Count()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen zurück. Nur lesbar int32_t.
type: docs
weight: 1
url: /de/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() Methode


Liefert die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. Nur lesbar **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## Hinweise


Beispiel: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## Siehe auch

* Klasse [IMathBlockCollection](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)