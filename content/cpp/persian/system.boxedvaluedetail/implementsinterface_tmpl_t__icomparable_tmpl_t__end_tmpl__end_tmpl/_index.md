---
title: ImplementsInterface< T, IComparable< T > >
second_title: Aspose.Slides برای C++ مرجع API
description: قالب پیش‌شرطی که بررسی می‌کند آیا شی جعبه‌شده باید به‌تنهایی رابط IComparable را پیاده‌سازی کند.
type: docs
weight: 53
url: /fa/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct


قالب پیش‌شرطی که بررسی می‌کند آیا شی بسته‌شده باید به‌تنهایی [IComparable](../../system/icomparable/) رابط را پیاده‌سازی کند.

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## موارد مرتبط

* فضای نام [System::BoxedValueDetail](../)
* کتابخانه [Aspose.Slides](../../)