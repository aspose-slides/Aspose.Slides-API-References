---
title: GetChars()
second_title: Aspose.Slides برای C++ مرجع API
description: کاراکترهایی که از رمزگشایی یک بافر بایت حاصل می‌شوند را دریافت می‌کند.
type: docs
weight: 274
url: /fa/system.text/encoding/getchars/
---
## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) متد

کاراکترهایی که از رمزگشایی یک بافر بایت حاصل می‌شوند را دریافت می‌کند.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |
| byte_index | int | آفست بافر ورودی. |
| byte_count | int | اندازه بافر ورودی. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها در. |
| char_index | int | آفست بافر خروجی. |

### مقدار بازگشتی

تعداد کاراکترهای نوشته شده.

## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) متد

کاراکترهایی که از رمزگشایی یک بافر بایت حاصل می‌شوند را دریافت می‌کند.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |
| index | int | آفست بافر ورودی. |
| count | int | اندازه بافر ورودی. |

### مقدار بازگشتی

[Buffer](../../../system/buffer/) از کاراکترهای رمزگشایی شده.

## Encoding::GetChars(ArrayPtr\<uint8_t\>) متد

کاراکترهایی که از رمزگشایی یک بافر بایت حاصل می‌شوند را دریافت می‌کند.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |

### مقدار بازگشتی

[Buffer](../../../system/buffer/) از کاراکترهای رمزگشایی شده.

## Encoding::GetChars(const uint8_t *, int, char_t *, int) متد

کاراکترهایی که از رمزگشایی یک بافر بایت حاصل می‌شوند را دریافت می‌کند.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |
| byte_count | int | اندازه بافر ورودی. |
| chars | char_t * | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها در. |
| char_count | int | اندازه بافر خروجی. |

### مقدار بازگشتی

تعداد کاراکترهای نوشته شده.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)