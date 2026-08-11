---
title: Seek()
second_title: مرجع API Aspose.Slides برای C++
description: موقعیت جریانی که توسط شیء جاری نمایندگی می‌شود را تنظیم می‌کند.
type: docs
weight: 79
url: /fa/system.io/stream/seek/
---
## Stream::Seek(int64_t, SeekOrigin) متد

موقعیت جریان که توسط شیء جاری نمایندگی می‌شود را تنظیم می‌کند.

```cpp
virtual int64_t System::IO::Stream::Seek(int64_t offset, SeekOrigin origin)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| offset | **int64_t** | افست بایت نسبت به موقعیتی که توسط **origin** مشخص شده است |
| origin | [SeekOrigin](../../seekorigin/) | موقعیتی را که از آن شروع می‌شود و جهت محاسبهٔ افست را تعیین می‌کند |

## مقدار بازگشت

موقعیت جدید جریان

## موارد مرتبط

* Enum [SeekOrigin](../../seekorigin/)
* کلاس [Stream](../)
* فضای نام [System::IO](../../)
* Library [Aspose.Slides](../../../)