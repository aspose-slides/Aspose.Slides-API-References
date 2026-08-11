---
title: IndexOf()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدّد فهرس عنصر IMathBlock محدد في المجموعة.
type: docs
weight: 79
url: /ar/aspose.slides.mathtext/imathblockcollection/indexof/
---
## IMathBlockCollection::IndexOf(System::SharedPtr\<IMathBlock\>) الطريقة


يحدد فهرس [IMathBlock](../../imathblock/) المحدد في المجموعة.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::IndexOf(System::SharedPtr<IMathBlock> item)=0
```


### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | العنصر لتحديد موقعه في المجموعة. |

### قيمة الإرجاع

فهرس *item* إذا وُجد في المجموعة؛ وإلا، -1.
## ملاحظات



مثال: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
int32_t index = blockCollection->IndexOf(block);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [IMathBlock](../../imathblock/)
* الفئة [IMathBlockCollection](../)
* الفضاء الاسمي [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)