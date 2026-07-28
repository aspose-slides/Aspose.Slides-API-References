---
title: get_Count()
second_title: Aspose.Slides C++ API-referencia
description: Visszaadja a gyűjteményben ténylegesen tárolt elemek számát. Csak olvasható int32_t.
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() metódus

Visszaadja a gyűjteményben ténylegesen tárolt elemek számát. Csak olvasható **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## Megjegyzések

Példa: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## Lásd még

* Osztály [IMathBlockCollection](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)