---
title: Ref()
second_title: Aspose.Slides برای C++ مرجع API
description: یک مرجع به شیء DynamicWeakPtr ایجاد می‌کند. توسط مترجم هنگام عبور آرگومان‌های تابع به صورت مرجع استفاده می‌شود.
type: docs
weight: 2458
url: /fa/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) تابع

یک مرجع به شی [DynamicWeakPtr](../dynamicweakptr/) ایجاد می‌کند. توسط مترجم هنگام عبور آرگومان‌های تابع به صورت مرجع استفاده می‌شود.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع اشاره‌گر. |
| trunkMode | حالت اشاره‌گر هوشمند خود. |
| weakLeafs | شاخص‌های آرگومان‌های قالب که برای آن‌ها باید متد SetTemplateWeakPtr فراخوانی شود. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | اشاره‌گر هوشمند برای ایجاد مرجع به آن. |

### مقدار بازگشت

مرجع اشاره‌گر هوشمند.

## System::Ref(T\&) تابع

تابع کمکی برای به‌دست آوردن مرجع‌ها به اشیاء. برای اطمینان از اینکه [System::DynamicWeakPtr](../dynamicweakptr/) پس از انتساب‌ها شی مرجع‌ شده را به‌روز می‌کند، استفاده می‌شود.

```cpp
template<typename T> T & System::Ref(T &value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع برای ایجاد مرجع به آن. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | T\& | مقداری که برای ایجاد مرجع به آن استفاده می‌شود. |

### مقدار بازگشت

مرجع به مقداری که به این تابع پاس داده شده است.

## موارد مرتبط

* کلاس [DynamicWeakPtr](../dynamicweakptr/)
* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)