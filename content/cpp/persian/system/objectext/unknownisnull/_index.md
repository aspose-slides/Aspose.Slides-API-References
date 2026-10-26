---
title: UnknownIsNull()
second_title: Aspose.Slides برای مرجع API C++
description: بررسی می‌کند که آیا شیء از نوع ناشناخته برابر nullptr است. بارگذاری برای انواع غیر اسکالاری.
type: docs
weight: 144
url: /fa/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) متد

بررسی می‌کند که آیا شیء از نوع ناشناخته برابر nullptr است. بارگذاری برای انواع غیر اسکالاری.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | [Object](../../object/) نوع. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | [Object](../../object/) برای بررسی. |

### مقدار بازگشت

درست اگر 'obj == nullptr' درست باشد، در غیر این صورت نادرست.

## ObjectExt::UnknownIsNull(T) متد

بررسی می‌کند که آیا شیء از نوع ناشناخته برابر nullptr است. بارگذاری برای انواع اسکالاری.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | [Object](../../object/) نوع. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | [Object](../../object/) برای بررسی. |

### مقدار بازگشت

همیشه نادرست برمی‌گرداند.

## موارد مرتبط

* کلاس [ObjectExt](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)