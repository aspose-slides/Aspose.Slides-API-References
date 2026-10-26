---
title: GetChars()
second_title: مرجع API Aspose.Slides برای C++
description: کاراکترهایی که از رمزگشایی یک بافر بایت به دست می‌آیند را دریافت می‌کند.
type: docs
weight: 66
url: /fa/system.text/icuencoding/getchars/
---
## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) متد


کاراکترهایی که از رمزگشایی یک بافر بایت به دست می‌آیند را دریافت می‌کند.

```cpp
int System::Text::ICUEncoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |
| byte_count | int | اندازهٔ بافر ورودی. |
| chars | char_t * | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها در. |
| char_count | int | اندازهٔ بافر خروجی. |

### مقدار بازگشت

تعداد کاراکترهای نوشته‌شده.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) متد


کاراکترهایی که از رمزگشایی یک بافر بایت به دست می‌آیند را دریافت می‌کند.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |
| byte_index | int | جابجایی بافر ورودی. |
| byte_count | int | اندازهٔ بافر ورودی. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها در. |
| char_index | int | جابجایی بافر خروجی. |

### مقدار بازگشت

تعداد کاراکترهای نوشته‌شده.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int) متد


کاراکترهایی که از رمزگشایی یک بافر بایت به دست می‌آیند را دریافت می‌کند.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |
| index | int | جابجایی بافر ورودی. |
| count | int | اندازهٔ بافر ورودی. |

### مقدار بازگشت

[Buffer](../../../system/buffer/) از کاراکترهای رمزگشایی‌شده.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>) متد


کاراکترهایی که از رمزگشایی یک بافر بایت به دست می‌آیند را دریافت می‌کند.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |

### مقدار بازگشت

[Buffer](../../../system/buffer/) از کاراکترهای رمزگشایی‌شده.

## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) متد


کاراکترهایی که از رمزگشایی یک بافر بایت به دست می‌آیند را دریافت می‌کند.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |
| byte_count | int | اندازهٔ بافر ورودی. |
| chars | char_t * | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها در. |
| char_count | int | اندازهٔ بافر خروجی. |

### مقدار بازگشت

تعداد کاراکترهای نوشته‌شده.

## موارد مرتبط

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [ICUEncoding](../)
* فضای‌نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)