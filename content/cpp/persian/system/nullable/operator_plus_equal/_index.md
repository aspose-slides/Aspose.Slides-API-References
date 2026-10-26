---
title: operator+=()
second_title: Aspose.Slides برای C++ مرجع API
description: شیء فعلی را بازنشانی می‌کند تا مقدار null را نمایش دهد.
type: docs
weight: 235
url: /fa/system/nullable/operator_plus_equal/
---
## Nullable::operator+=(std::nullptr_t) method

شیء فعلی را بازنشانی می‌کند تا مقدار null را نمایش دهد.

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```

### Return Value

یک کپی از خود

## Nullable::operator+=(const T1\&) method

[operator+=()](./) را بر مقدار نمایان‌سازی‌شده توسط شیء فعلی اعمال می‌کند، با استفاده از مقدار مشخص‌شده به‌عنوان آرگومان سمت راست.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | نوع مقدار مورد استفاده به‌عنوان مقدار سمت راست [operator+=()](./) |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | یک مرجع ثابت به مقداری که به‌عنوان مقدار سمت راست [operator+=()](./) اعمال شده‌ بر مقدار نمایان‌سازی‌شده توسط شیء فعلی استفاده می‌شود. |

### Return Value

یک مرجع به خود

## Nullable::operator+=(const Nullable\<T1\>\&) method

[operator+=()](./) را بر مقدار نمایان‌سازی‌شده توسط شیء فعلی اعمال می‌کند، با استفاده از مقدار نمایان‌سازی‌شده توسط شیء [Nullable](../) مشخص‌شده به‌عنوان آرگومان سمت راست.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | نوع پایهٔ یک شیء [Nullable](../) که مقدار نمایان‌سازی‌شده توسط آن به‌عنوان آرگومان سمت راست [operator+=()](./) استفاده می‌شود |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | یک مرجع ثابت به شیء [Nullable](../) که مقدار نمایان‌سازی‌شده توسط آن به‌عنوان آرگومان سمت راست [operator+=()](./) اعمال‌شده بر مقدار نمایان‌سازی‌شده توسط شیء فعلی استفاده می‌شود. |

### Return Value

یک مرجع به خود

## See Also

* کلاس [Nullable](../)
* ساختار [IsNullable](../../isnullable/)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)