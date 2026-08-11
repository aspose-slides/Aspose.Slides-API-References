---
title: Read()
second_title: Aspose.Slides برای مرجع API C++
description: یک کاراکتر واحد را از جریان ورودی می‌خواند.
type: docs
weight: 66
url: /fa/system.io/binaryreader/read/
---
## متد BinaryReader::Read() method

یک کاراکتر واحد را از جریان ورودی می‌خواند.

```cpp
virtual int System::IO::BinaryReader::Read()
```

### مقدار بازگشت

کاراکتر خوانده شده با کدگذاری UTF-16؛ اگر کاراکتر خوانده شده توسط دو کد پوینت در کدگذاری UTF-16 نمایان شود، تنها high surrogate بازگردانده می‌شود.

## متد BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) method

تعداد مشخصی از بایت‌ها را از جریان ورودی می‌خواند و آن‌ها را در آرایه بایتی مشخص‌شده می‌نویسد.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایتی که بایت‌های خوانده‌شده در آن نوشته می‌شوند |
| index | int | موقعیتی مبتنی بر صفر در **buffer** که نوشتن از آن آغاز می‌شود |
| count | int | تعداد بایت‌هایی که باید خوانده شوند |

### مقدار بازگشت

تعداد بایت‌های خوانده‌شده

## متد BinaryReader::Read(ArrayPtr\<char_t\>, int, int) method

تعداد مشخصی از کاراکترها را از جریان ورودی می‌خواند، آن‌ها را به کدگذاری UTF-16 تبدیل می‌کند و کاراکترهای نتیجه‌گیری شده UTF-16 را در آرایه کاراکتری مشخص‌شده، از موقعیت مشخص‌شده، می‌نویسد.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | آرایه کاراکتری UTF-16 که کاراکترهای خوانده‌شده از جریان ورودی در آن نوشته می‌شوند |
| index | int | ایندکسی مبتنی بر صفر در **buffer** که نوشتن از آن آغاز می‌شود |
| count | int | تعداد کاراکترهایی که باید از جریان خوانده شوند |

### مقدار بازگشت

تعداد کاراکترهای خوانده‌شده از جریان ورودی

## همچنین

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BinaryReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)