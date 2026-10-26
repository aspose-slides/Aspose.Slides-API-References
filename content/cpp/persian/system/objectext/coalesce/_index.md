---
title: Coalesce()
second_title: مرجع API Aspose.Slides برای C++
description: پیاده‌سازی ترجمه عملگر '??' برای انواع غیرقابل null.
type: docs
weight: 170
url: /fa/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) متد

پیاده‌سازی ترجمه عملگر '??' برای انواع غیرقابل null.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T0 | نوع مقدار LHS. |
| T1 | نوع lambda که عبارت RHS را محصور می‌کند. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | T0 | مقدار LHS. |
| func | T1 | عبارت RHS. |

### Return Value

اگر مقدار LHS تهی (null) نیست، مقدار LHS را برمی‌گرداند، در غیر این صورت عبارت RHS را محاسبه کرده و نتیجه را برمی‌گرداند.

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) متد

پیاده‌سازی ترجمه عملگر '??' برای انواع قابل null.

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T0 | نوع مقدار LHS. |
| T1 | نوع lambda که عبارت RHS را محصور می‌کند. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | مقدار LHS. |
| func | T1 | عبارت RHS. |

### Return Value

اگر مقدار LHS تهی (null) نیست، مقدار LHS را برمی‌گرداند، در غیر این صورت عبارت RHS را محاسبه کرده و نتیجه را برمی‌گرداند.

## موارد مرتبط

* کلاس [ObjectExt](../)
* کلاس [Nullable](../../nullable/)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)