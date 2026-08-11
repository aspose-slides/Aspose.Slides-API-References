---
title: idx_get()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحصل على العنصر في الفهرس المحدد. للقراءة فقط IMathBlock.
type: docs
weight: 92
url: /ar/aspose.slides.mathtext/imathblockcollection/idx_get/
---
## IMathBlockCollection::idx_get(int32_t) طريقة

يحصل على العنصر في الفهرس المحدد. للقراءة فقط [IMathBlock](../../imathblock/).

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockCollection::idx_get(int32_t index)=0
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري للعنصر المراد الحصول عليه |

### قيمة الإرجاع

كتلة نص رياضي.

## ملاحظات



مثال: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = blockCollection->idx_get(1);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathBlock](../../imathblock/)
* فئة [IMathBlockCollection](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)