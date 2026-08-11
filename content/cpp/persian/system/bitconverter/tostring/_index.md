---
title: ToString()
second_title: راهنمای API Aspose.Slides برای C++
description: تمام مقادیر آرایه بایتی مشخص‌شده را به نمایهٔ رشته‌ای شانبه‌شده تبدیل می‌کند. حالت حروف استفاده‌شده در نمایش شانبه‌شده و جداکننده‌ای که بین هر جفت بایت همسایه قرار می‌گیرد، از طریق آرگومان‌های مربوطه تعیین می‌شوند.
type: docs
weight: 157
url: /fa/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) متد

تمام مقادیر آرایه بایتی تعیین‌شده را به نمایش رشته‌ای شانبه‌شدهای تبدیل می‌کند. حالت حروف مورد استفاده در نمایش شانبه‌شد و جداکننده‌ای که بین هر جفت بایت همسایه وارد می‌شود، از طریق آرگومان‌های متناظر مشخص می‌شود.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) که شامل بایت‌های تبدیل‌شدنی است |
| uppercase | **bool** | حالت حروف مورد استفاده در نمایش شانبه‌شد نهایی را مشخص می‌کند |
| separator | const [String](../../string/)\& | رشته‌ای که به عنوان جداکننده بین هر جفت بایت همسایه در رشته نهایی وارد می‌شود |

### مقدار بازگشت

[String](../../string/) شامل نمایش شانبه‌شدهای آرایه بایتی تعیین‌شده

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) متد

مقادیر آرایه بایتی تعیین‌شده را به نمایش رشته‌ای شانبه‌شدهای تبدیل می‌کند که از ایندکس مشخص‌شده شروع می‌شوند.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) که شامل بایت‌های تبدیل‌شدنی است |
| startIndex | int | [Index](../../index/) در آرایهٔ تعیین‌شده که تبدیل از آن شروع می‌شود |

### مقدار بازگشت

[String](../../string/) شامل نمایش شانبه‌شدهای محدودهٔ مشخصی از عناصر آرایهٔ تعیین‌شده

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) متد

محدوده‌ای از مقادیر آرایه بایتی تعیین‌شده را به نمایش رشته‌ای شانبه‌شدهای تبدیل می‌کند.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) که شامل بایت‌های تبدیل‌شدنی است |
| startIndex | int | [Index](../../index/) در آرایهٔ تعیین‌شده که محدودهٔ عناصر آرایه بایت برای تبدیل از آن شروع می‌شود |
| length | int | طول محدوده‌ای از عناصر آرایه بایت که باید تبدیل شوند |

### مقدار بازگشت

[String](../../string/) شامل نمایش شانبه‌شدهای محدودهٔ مشخصی از عناصر آرایهٔ تعیین‌شده

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../arrayptr/)
* کلاس [String](../../string/)
* کلاس [BitConverter](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)