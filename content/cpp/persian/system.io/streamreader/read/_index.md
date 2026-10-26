---
title: Read()
second_title: Aspose.Slides برای C++ مرجع API
description: یک کاراکتر را از جریان می‌خواند.
type: docs
weight: 40
url: /fa/system.io/streamreader/read/
---
## StreamReader::Read() متد

یک کاراکتر را از جریان می‌خواند.

```cpp
virtual int System::IO::StreamReader::Read() override
```

### مقدار بازگشت

کاراکتر خوانده شده با رمزگذاری UTF-16 بازگردانده می‌شود؛ اگر کاراکتر خوانده شده توسط دو کد نقطه در رمزگذاری UTF-16 نمایان شود، فقط سورروگیت بالایی بازگردانده می‌شود.

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) متد

تعداد مشخصی از کاراکترها را از جریان می‌خواند، آن‌ها را به رمزگذاری UTF-16 تبدیل می‌کند و کاراکترهای حاصل شده با رمزگذاری UTF-16 را در آرایه کاراکتر مشخص شده، از موقعیت تعیین‌شده آغاز می‌کند.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | آرایه کاراکتر UTF-16 برای نوشتن کاراکترهای خوانده‌شده از جریان |
| index | int | یک ایندکس صفر-محور در **buffer** که نوشتن از آن آغاز می‌شود |
| count | int | تعداد کاراکترهایی که از جریان خوانده می‌شوند |

### مقدار بازگشت

تعداد کاراکترهای خوانده‌شده از جریان

## موارد مرتبط

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [StreamReader](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)