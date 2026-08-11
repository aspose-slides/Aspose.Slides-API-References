---
title: Insert()
second_title: Aspose.Slides برای مرجع API C++
description: یک عنصر ریاضی را در مجموعه در ایندکس مشخص شده وارد می‌کند.
type: docs
weight: 53
url: /fa/aspose.slides.mathtext/imathelementcollection/insert/
---
## IMathElementCollection::Insert(int32_t, System::SharedPtr\<IMathElement\>) متد

یک عنصر ریاضی را در مجموعه در ایندکس مشخص شده وارد می‌کند.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::Insert(int32_t index, System::SharedPtr<IMathElement> item)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | ایندکس صفر-مبنا که [IMathElement](../../imathelement/) باید در آن وارد شود. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | [IMathElement](../../imathelement/) برای وارد کردن. |
## توضیحات

مثال: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [IMathElementCollection](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)