---
title: Cast()
second_title: مرجع API Aspose.Slides برای C++
description: تبدیل را بر روی اشیای SmartPtr انجام می‌دهد.
type: docs
weight: 2510
url: /fa/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) تابع


تبدیل را بر روی اشیای [SmartPtr](../smartptr/) انجام می‌دهد.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```


### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TTo | نوع اشاره‌گر مقصد. |
| TFrom | نوع اشاره‌گر منبع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | اشاره‌گر منبع. |

### مقدار بازگشتی

نتیجهٔ تبدیل اگر تبدیل مجاز باشد.

## موارد مرتبط

* کلاس [SmartPtr](../smartptr/)
* ساختار [IsExceptionWrapper](../isexceptionwrapper/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)