---
title: RemoveAt()
second_title: مرجع API Aspose.Slides برای C++
description: عنصری که در اندیس مشخص‌شده از مجموعه قرار دارد را حذف می‌کند.
type: docs
weight: 105
url: /fa/aspose.slides.mathtext/imathelementcollection/removeat/
---
## IMathElementCollection::RemoveAt(int32_t) متد


عنصر موجود در اندیس مشخص شده از مجموعه را حذف می‌کند.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::RemoveAt(int32_t index)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفر مبنایی عنصری که باید حذف شود. |
## توضیحات



مثال: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->RemoveAt(2);
```

## موارد مرتبط

* کلاس [IMathElementCollection](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)