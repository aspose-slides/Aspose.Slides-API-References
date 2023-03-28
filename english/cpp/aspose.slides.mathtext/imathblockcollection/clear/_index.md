---
title: Clear()
second_title: Aspose.Slides for C++ API Reference
description: Removes all elements from the collection.
type: docs
weight: 118
url: /cpp/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() method


Removes all elements from the collection.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## Remarks


Example: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## See Also

* Class [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
