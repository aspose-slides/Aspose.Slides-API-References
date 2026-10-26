---
title: UnmanagedMemoryStream()
second_title: Aspose.Slides برای مرجع API C++
description: یک نمونه جدید از UnmanagedMemoryStream ایجاد می‌کند.
type: docs
weight: 118
url: /fa/system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) سازنده

یک نمونه جدید از [UnmanagedMemoryStream](../) ایجاد می‌کند.

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pointer | **uint8_t** * | یک اشاره‌گر به بافر غیر‌مدیریت‌شده |
| length | **int64_t** | اندازهٔ بافر غیر‌مدیریت‌شده بر حسب بایت |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) سازنده

یک نمونه جدید از [UnmanagedMemoryStream](../) ایجاد می‌کند.

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pointer | **uint8_t** * | یک اشاره‌گر به بافر غیر‌مدیریت‌شده |
| length | **int64_t** | اندازهٔ بافر غیر‌مدیریت‌شده بر حسب بایت |
| capacity | **int64_t** | کل حافظه اختصاص‌یافته به جریان |
| access | [FileAccess](../../fileaccess/) | مشخص می‌کند که آیا جریان باید فقط-خواندنی، write-onle یا هر دو باشد |

## موارد مرتبط

* شمارش [FileAccess](../../fileaccess/)
* کلاس [UnmanagedMemoryStream](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)