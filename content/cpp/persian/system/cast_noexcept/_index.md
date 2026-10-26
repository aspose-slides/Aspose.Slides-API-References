---
title: Cast_noexcept()
second_title: مرجع API Aspose.Slides برای C++
description: تبدیل را بر روی اشیای SmartPtr انجام می‌دهد.
type: docs
weight: 2497
url: /fa/system/cast_noexcept/
---
## System::Cast_noexcept(SmartPtr\<TFrom\> const\&) تابع

عملیات تبدیل روی اشیای [SmartPtr](../smartptr/) انجام می‌دهد.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| TTo | نوع اشاره‌گر هدف. |
| TFrom | نوع اشاره‌گر منبع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | اشاره‌گر منبع. |

### مقدار بازگشت

نتیجهٔ تبدیل اگر تبدیل مجاز باشد یا nullptr در غیر این صورت.

## مراجعه

* کلاس [SmartPtr](../smartptr/)
* ساختار [IsExceptionWrapper](../isexceptionwrapper/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)