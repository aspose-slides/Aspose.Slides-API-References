---
title: BinarySearchImpl()
second_title: Aspose.Slides برای C++ مرجع API
description: اجرای عمومی جستجوی دودویی.
type: docs
weight: 118
url: /fa/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) تابع

اجرای عمومی جستجوی دودویی.

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T | نوع عناصر در بازه |
| TValue | نوع مقدار برای جستجو |
| TCompareFunc | نوع تابع برای مقایسه |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | بازه‌ای که باید جستجو شود |
| value | const TValue\& | مقداری که باید جستجو شود |
| compareFunc | TCompareFunc | تابعی که مقدار را با عنصر بازه مقایسه می‌کند و **int32_t** (-1, 0, 1) برمی‌گرداند |

### مقدار بازگشت

[Index](../../system/index/) عنصر یافت‌شده یا مکمل بیتی نقطه درج

## موارد مرتبط

* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* فضای‌نام [System::MemoryExtensions::Details](../)
* کتابخانه [Aspose.Slides](../../)