---
title: Clear()
second_title: Aspose.Slides لمرجع API C++
description: يزيل جميع العناصر من التجميع.
type: docs
weight: 118
url: /ar/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() طريقة


يزيل جميع العناصر من التجميع.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## ملاحظات


مثال:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## انظر أيضًا

* فئة [IMathBlockCollection](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)