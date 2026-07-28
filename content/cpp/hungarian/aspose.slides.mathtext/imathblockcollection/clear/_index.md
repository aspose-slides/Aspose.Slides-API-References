---
title: Clear()
second_title: Aspose.Slides C++ API referencia
description: Eltávolítja az összes elemet a gyűjteményből.
type: docs
weight: 118
url: /hu/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() metódus


Eltávolítja az összes elemet a gyűjteményből.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## Megjegyzések


Példa: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## Lásd még

* Osztály [IMathBlockCollection](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)