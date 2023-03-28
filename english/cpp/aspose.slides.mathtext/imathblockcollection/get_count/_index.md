---
title: get_Count()
second_title: Aspose.Slides for C++ API Reference
description: Gets the number of elements actually contained in the collection. Read-only int32_t.
type: docs
weight: 1
url: /cpp/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() method


Gets the number of elements actually contained in the collection. Read-only **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## Remarks


Example: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## See Also

* Class [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
