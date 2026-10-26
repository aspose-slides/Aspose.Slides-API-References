---
title: get_Count()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad int32_t.
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() metod


Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## Anmärkningar


Exempel: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## Se även

* Klass [IMathBlockCollection](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)