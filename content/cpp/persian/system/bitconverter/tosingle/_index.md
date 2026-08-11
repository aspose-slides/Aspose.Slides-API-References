---
title: ToSingle()
second_title: Aspose.Slides برای C++ مرجع API
description: چهار بایت را از آرایهٔ مشخص‌شده که از اندیس تعیین‌شده شروع می‌شود، به مقدار عدد شناور با دقت تک‌تایی تبدیل می‌کند.
type: docs
weight: 131
url: /fa/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) متد

چهار بایت از آرایهٔ مشخص‌شده را که از اندیس مشخص شروع می‌شوند، به مقدار عدد حقیقی با دقت تک‌تایی تبدیل می‌کند.

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) که شامل بایت‌های قابل تبدیل است |
| startIndex | int | [Index](../../index/) در آرایه‌ای که برای شروع استخراج بایت‌ها جهت تبدیل استفاده می‌شود |

### مقدار بازگشت

مقدار عدد حقیقی با دقت تک‌تایی حاصل از تبدیل

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) متد

چهار بایت از آرایهٔ مشخص‌شده را که از اندیس مشخص شروع می‌شوند، به مقدار عدد حقیقی با دقت تک‌تایی تبدیل می‌کند.

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView که شامل بایت‌های قابل تبدیل است |
| startIndex | int | [Index](../../index/) در آرایه‌ای که برای شروع استخراج بایت‌ها جهت تبدیل استفاده می‌شود |

### مقدار بازگشت

مقدار عدد حقیقی با دقت تک‌تایی حاصل از تبدیل

## موارد مرتبط

* نوع‌تعریف [ArrayPtr](../../arrayptr/)
* کلاس [BitConverter](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)