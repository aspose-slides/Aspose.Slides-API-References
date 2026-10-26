---
title: Equals()
second_title: Aspose.Slides برای C++ API مرجع
description: تعیین می‌کند آیا ناحیهٔ مشخص شده با ناحیه‌ای که توسط شیء فعلی روی سطح رسم مشخص‌شده نمایان می‌شود یکسان است.
type: docs
weight: 157
url: /fa/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) متد

تعیین می‌کند آیا ناحیهٔ مشخص شده با ناحیهٔ نمایان شده توسط شیء فعلی روی سطح رسم مشخص شده یکسان است.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | ناحیه‌ای که این ناحیه با آن مقایسه می‌شود |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | سطح رسم |

### مقدار بازگشت

True اگر داخل ناحیهٔ مشخص شده با داخل ناحیه‌ای که توسط شیء فعلی نمایان می‌شود وقتی تبدیل مرتبط با پارامتر **g** اعمال می‌شود یکسان باشد؛ در غیر این صورت - false

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Region](../)
* کلاس [Graphics](../../graphics/)
* فضای‌نام [System::Drawing](../../)
* کتابخانه [Aspose.Slides](../../../)