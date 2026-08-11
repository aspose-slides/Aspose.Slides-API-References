---
title: FromBase64CharArray()
second_title: مرجع API Aspose.Slides برای C++
description: داده‌های رمزگذاری شده با base-64 که به‌صورت یک بازه در آرایه‌ای از کاراکترهای یونیکد نمایش داده شده‌اند، را رمزگشایی می‌کند.
type: docs
weight: 53
url: /fa/system/convert/frombase64chararray/
---
## Convert::FromBase64CharArray(const ArrayPtr\<char_t\>\&, int, int) متد

داده‌های رمزگذاری شده با base-64 که به‌صورت یک بازه در آرایه‌ای از کاراکترهای یونیکد نمایش داده شده‌اند، را رمزگشایی می‌کند.

```cpp
static ArrayPtr<uint8_t> System::Convert::FromBase64CharArray(const ArrayPtr<char_t> &in_array, int offset, int length)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | آرایه‌ای که حاوی داده‌های مورد رمزگشایی است |
| offset | int | موقعیتی در آرایه ورودی که بازه برای رمزگشایی از آن شروع می‌شود |
| length | int | طول بازه‌ای که باید رمزگشایی شود |

### مقدار بازگشت

یک آرایه بایت حاوی داده‌های رمزگشایی‌شده

## موارد مرتبط

* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)