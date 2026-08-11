---
title: IsDBNull()
second_title: مرجع API Aspose.Slides برای C++
description: پیاده‌سازی نشده.
type: docs
weight: 14
url: /fa/system/convert/isdbnull/
---
## Convert::IsDBNull(const T\&) متد


پیاده‌سازی نشده.

```cpp
template<typename T> static std::enable_if_t<!IsSmartPtr<T>::value, bool> System::Convert::IsDBNull(const T &)
```


## Convert::IsDBNull(const SharedPtr\<T\>\&) متد


پیاده‌سازی نشده. پیاده‌سازی ساختگی، بررسی می‌کند آیا مقدار nullptr است.

```cpp
template<typename T> static bool System::Convert::IsDBNull(const SharedPtr<T> &value)
```

## همچنین ببینید

* تعریف نوع [SharedPtr](../../sharedptr/)
* ساختار [IsSmartPtr](../../issmartptr/)
* ساختار [Convert](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)