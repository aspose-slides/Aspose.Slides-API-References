---
title: GetChildRows()
second_title: مرجع API Aspose.Slides برای C++
description: ردیف‌هایی را که از طریق رابطه مشخص به عنوان فرزند در نظر گرفته می‌شوند، دریافت می‌کند.
type: docs
weight: 27
url: /fa/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) متد

ردیف‌هایی را که از طریق رابطه مشخص به عنوان فرزند در نظر گرفته می‌شوند، دریافت می‌کند.

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | شیء Relation برای تعیین رابطه ردیف والد - ردیف فرزند. |

### مقدار بازگشت

[Array](../../../system/array/) از ردیف‌های فرزند بازیابی شده.

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [DataRow](../)
* کلاس [DataRelation](../../datarelation/)
* فضای نام [System::Data](../../)
* کتابخانه [Aspose.Slides](../../../)