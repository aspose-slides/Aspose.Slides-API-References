---
title: idx_get()
second_title: مرجع API Aspose.Slides برای C++
description: عنصر را در اندیس مشخص شده دریافت می‌کند. فقط‌خواندنی IMathElement.
type: docs
weight: 14
url: /fa/aspose.slides.mathtext/imathelementcollection/idx_get/
---
## IMathElementCollection::idx_get(int32_t) متد

عنصر را در اندیس مشخص شده دریافت می‌کند. فقط‌خواندنی [IMathElement](../../imathelement/).

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathElementCollection::idx_get(int32_t index)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | اندیس صفرپایه‌ای موردی که می‌خواهید دریافت کنید |
## توضیحات

مثال:
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = collection->idx_get(0);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [IMathElementCollection](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)