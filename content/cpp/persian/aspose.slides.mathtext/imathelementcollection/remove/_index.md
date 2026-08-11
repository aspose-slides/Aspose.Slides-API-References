---
title: Remove()
second_title: Aspose.Slides برای C++ API Reference
description: اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند.
type: docs
weight: 92
url: /fa/aspose.slides.mathtext/imathelementcollection/remove/
---
## IMathElementCollection::Remove(System::SharedPtr\<IMathElement\>) متد


اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Remove(System::SharedPtr<IMathElement> item)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | شیء‌ای که باید از مجموعه حذف شود. |

### مقدار بازگشت

true اگر *item* با موفقیت از مجموعه حذف شده باشد؛ در غیر این صورت false. این متد همچنین false را برمی‌گرداند اگر *item* در مجموعه اصلی یافت نشود.
## توضیحات



مثال: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->Remove(plusElement);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [IMathElementCollection](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)