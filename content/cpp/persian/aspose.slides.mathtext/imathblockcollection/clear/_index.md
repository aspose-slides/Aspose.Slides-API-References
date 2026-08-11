---
title: Clear()
second_title: Aspose.Slides برای C++ مرجع API
description: تمام عناصر را از مجموعه حذف می‌کند.
type: docs
weight: 118
url: /fa/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() متد

تمام عناصر را از مجموعه حذف می‌کند.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## توضیحات

مثال: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## موارد مرتبط

* کلاس [IMathBlockCollection](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)