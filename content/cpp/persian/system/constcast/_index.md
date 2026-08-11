---
title: ConstCast()
second_title: مرجع API Aspose.Slides برای C++
description: پایان تبدیل‌های منسوخ شده.
type: docs
weight: 2575
url: /fa/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) تابع

پایان تبدیل‌های منسوخ شده.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TTo | نوع شیء هدف. |
| TFrom | نوع شیء منبع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | اشاره‌گر منبع. |

### مقدار بازگشت

نتیجه تبدیل در صورتی که تبدیل مجاز باشد یا در غیر این صورت nullptr.

## توضیحات

یک تبدیل const بر روی اشیای [SmartPtr](../smartptr/) انجام می‌دهد.

## موارد مرتبط

* کلاس [SmartPtr](../smartptr/)
* ساختار [CastResult](../castresult/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)