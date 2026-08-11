---
title: Span
second_title: Aspose.Slides برای C++ مرجع API
description: "نمایانگر یک ناحیهٔ پیوسته از حافظهٔ دلخواه مشابه std::span در C++20 است."
type: docs
weight: 1262
url: /fa/system/span/
---
## کلاس Span

نمایانگر یک ناحیهٔ پیوسته از حافظهٔ دلخواه مشابه std::span در C++20 است.

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع المان‌های موجود در span. این کلاس روشی ایمن از نظر نوع برای کار با توالی‌های پیوسته از اشیاء فراهم می‌کند. می‌تواند برای بسته‌بندی آرایه‌ها، آرایه‌های پشته‌ای یا اشاره‌گرهای خام استفاده شود در حالی که بررسی مرزها را حفظ می‌کند. [Span](./) مالک حافظه‌ای که به آن اشاره می‌کند نیست - تنها نمایی از حافظهٔ موجود است. |

## متدها

| Method | Description |
| --- | --- |
| void [Clear](./clear/)() const | محتویات span را با تنظیم تمام المان‌ها به مقدار پیش‌فرض پاک می‌کند. |
| void [Fill](./fill/)(const T\&) const | span را با مقدار مشخص شده پر می‌کند. |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | یک آرایه را به [Span](./) تبدیل می‌کند. |

## موارد مرتبط

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)