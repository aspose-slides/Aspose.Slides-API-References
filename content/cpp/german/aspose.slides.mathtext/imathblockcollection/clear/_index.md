---
title: Clear()
second_title: Aspose.Slides für C++ API-Referenz
description: Entfernt alle Elemente aus der Sammlung.
type: docs
weight: 118
url: /de/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() Methode


Entfernt alle Elemente aus der Sammlung.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## Hinweise


Beispiel:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## Siehe auch

* Klasse [IMathBlockCollection](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)