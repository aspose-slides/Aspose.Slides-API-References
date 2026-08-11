---
title: GetChars()
second_title: مرجع API Aspose.Slides برای C++
description: کاراکترهایی که از رمزگشایی یک بافر بایت به‌دست می‌آیند را دریافت می‌کند.
type: docs
weight: 92
url: /fa/system.text/utf7encoding/getchars/
---
## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) متد

کاراکترهایی که از رمزگشایی یک بافر بایت به‌دست می‌آیند را دریافت می‌کند.

```cpp
int System::Text::UTF7Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |
| byte_index | int | آفست بافر ورودی. |
| byte_count | int | اندازه بافر ورودی. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) برای ذخیره کردن کاراکترها به. |
| char_index | int | آفست بافر خروجی. |

### مقدار بازگشت

تعداد کاراکترهای نوشته‌شده.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) متد

کاراکترهایی که از رمزگشایی یک بافر بایت به‌دست می‌آیند را دریافت می‌کند.

```cpp
int System::Text::UTF7Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |
| byte_count | int | اندازه بافر ورودی. |
| chars | char_t * | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها به. |
| char_count | int | اندازه بافر خروجی. |

### مقدار بازگشت

تعداد کاراکترهای نوشته‌شده.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) متد

کاراکترهایی که از رمزگشایی یک بافر بایت به‌دست می‌آیند را دریافت می‌کند.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |
| byte_index | int | آفست بافر ورودی. |
| byte_count | int | اندازه بافر ورودی. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها به. |
| char_index | int | آفست بافر خروجی. |

### مقدار بازگشت

تعداد کاراکترهای نوشته‌شده.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) متد

کاراکترهایی که از رمزگشایی یک بافر بایت به‌دست می‌آیند را دریافت می‌کند.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |
| index | int | آفست بافر ورودی. |
| count | int | اندازه بافر ورودی. |

### مقدار بازگشت

[Buffer](../../../system/buffer/) کاراکترهای رمزگشایی‌شده.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>) متد

کاراکترهایی که از رمزگشایی یک بافر بایت به‌دست می‌آیند را دریافت می‌کند.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |

### مقدار بازگشت

[Buffer](../../../system/buffer/) کاراکترهای رمزگشایی‌شده.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) متد

کاراکترهایی که از رمزگشایی یک بافر بایت به‌دست می‌آیند را دریافت می‌کند.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |
| byte_count | int | اندازه بافر ورودی. |
| chars | char_t * | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها به. |
| char_count | int | اندازه بافر خروجی. |

### مقدار بازگشت

تعداد کاراکترهای نوشته‌شده.

## موارد مرتبط

* نوع‌تعریف [ArrayPtr](../../../system/arrayptr/)
* کلاس [UTF7Encoding](../)
* فضای‌نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)