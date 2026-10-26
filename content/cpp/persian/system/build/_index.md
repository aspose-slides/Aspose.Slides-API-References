---
title: Build()
second_title: Aspose.Slides برای مرجع API C++
description: یک شیء را با مالکیت مستقیم بسازید.
type: docs
weight: 2289
url: /fa/system/build/
---
## System::Build(Args\&&...) تابع

یک شیء را با مالکیت مستقیم بسازید.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء برای ساخت |
| Args | نوع آرگومان‌ها برای ساخت شیء |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| args | Args\&&... | آرگومان‌ها برای ارسال به سازندهٔ شیء |

### مقدار بازگشت

ObjectBuilder پیکربندی‌شده برای ساخت مستقیم شیء

## ملاحظات

[Object](../object/) ساخت باید با فراخوانی [Get()](../get/) به پایان برسد

## موارد مرتبط

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)