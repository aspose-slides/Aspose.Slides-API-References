---
title: idx_set()
second_title: Aspose.Slides للغة C++ مرجع API
description: يحصل على العنصر عند الفهرس المحدد. للقراءة فقط IMathBlock.
type: docs
weight: 105
url: /ar/aspose.slides.mathtext/imathblockcollection/idx_set/
---
## طريقة IMathBlockCollection::idx_set(int32_t, System::SharedPtr\<IMathBlock\>)  

يسترجع العنصر عند الفهرس المحدد. للقراءة فقط [IMathBlock](../../imathblock/).

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::idx_set(int32_t index, System::SharedPtr<IMathBlock> value)=0
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الفهرس الصفري للعنصر المطلوب استرجاعه |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | الكتلة النصية الرياضية. |
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
* مساحة اسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)