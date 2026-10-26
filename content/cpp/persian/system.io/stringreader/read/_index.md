---
title: Read()
second_title: مرجع API Aspose.Slides برای C++
description: یک کاراکتر از جریان می‌خواند.
type: docs
weight: 40
url: /fa/system.io/stringreader/read/
---
## StringReader::Read() متد

یک کاراکتر از جریان می‌خواند.

```cpp
virtual int System::IO::StringReader::Read() override
```

### مقدار بازگشت

یک کاراکتر خوانده‌شده یا -1 اگر کاراکتری خوانده نشود

## StringReader::Read(ArrayPtr\<char_t\>, int, int) متد

تعداد مشخص‌شده‌ای از کاراکترها را از جریان به آرایه کاراکتری مشخص‌شده که از موقعیت مشخص‌شده شروع می‌شود، می‌خواند.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | آرایه کاراکتری که کاراکترهای خوانده‌شده از جریان در آن نوشته می‌شوند |
| index | int | یک اندیس مبتنی بر صفر در **buffer** که نوشتن از آن آغاز می‌شود |
| count | int | تعداد کاراکترهایی که از جریان خوانده می‌شوند |

### مقدار بازگشت

تعداد کاراکترهای خوانده‌شده از جریان

## همچنین ببینید

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [StringReader](../)
* فضای نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)