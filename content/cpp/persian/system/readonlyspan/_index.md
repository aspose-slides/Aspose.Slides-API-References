---
title: ReadOnlySpan
second_title: مرجع API Aspose.Slides برای C++
description: جهت استفاده در کلاس Span
type: docs
weight: 1210
url: /fa/system/readonlyspan/
---
## کلاس ReadOnlySpan

برای استفاده در کلاس [Span](../span/).

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه. این کلاس یک روش ایمن نوع برای کار با توالی‌های پیوسته از اشیاء به صورت فقط-خواندنی فراهم می‌کند. می‌تواند برای بسته‌بندی آرایه‌ها، آرایه‌های پشته‌ای، یا اشاره‌گرهای خام استفاده شود در حالی که بررسی مرزها را حفظ می‌کند. [ReadOnlySpan](./) مالک حافظه‌ای که به آن اشاره می‌کند نیست - فقط یک نمایه از حافظه موجود است. |

## متدها

| متد | توضیح |
| --- | --- |
| [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | یک بازه فقط-خواندنی را از یک بازه معمولی می‌سازد. |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | یک آرایه را به [ReadOnlySpan](./) تبدیل می‌کند. |

## توضیحات

یک ناحیه پیوسته فقط-خواندنی از حافظهٔ دلخواه را نشان می‌دهد.

## موارد مرتبط

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)