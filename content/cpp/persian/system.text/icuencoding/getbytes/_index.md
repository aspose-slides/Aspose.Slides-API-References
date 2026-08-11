---
title: GetBytes()
second_title: مرجع API Aspose.Slides برای C++
description: بایت‌هایی که از کدگذاری یک بافر کاراکتر به دست می‌آیند را دریافت کنید.
type: docs
weight: 40
url: /fa/system.text/icuencoding/getbytes/
---
## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) متد

بایت‌های حاصل از کدگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
int System::Text::ICUEncoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | const char_t * | کاراکترهای برای کدگذاری. |
| char_count | int | تعداد کاراکترهای قابل تبدیل. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها. |
| byte_count | int | اندازهٔ بافر خروجی. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) متد

بایت‌های حاصل از کدگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | کاراکترهای برای کدگذاری. |
| char_index | int | شروع برش کاراکتر. |
| char_count | int | تعداد کاراکترهای قابل تبدیل. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها. |
| byte_index | int | موقعیت بافر خروجی. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## ICUEncoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) متد

بایت‌های حاصل از کدگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | کاراکترهای برای کدگذاری. |
| char_index | int | شروع برش کاراکتر. |
| char_count | int | تعداد کاراکترهای قابل تبدیل. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها. |
| byte_index | int | موقعیت بافر خروجی. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## ICUEncoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) متد

بایت‌های حاصل از کدگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | کاراکترهای برای کدگذاری. |
| char_index | int | شروع برش کاراکتر. |
| char_count | int | تعداد کاراکترهای قابل تبدیل. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها. |
| byte_index | int | موقعیت بافر خروجی. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## ICUEncoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) متد

بایت‌های حاصل از کدگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) برای کدگذاری. |
| char_index | int | شروع برش کاراکتر. |
| char_count | int | تعداد کاراکترهای قابل تبدیل. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها. |
| byte_index | int | موقعیت بافر خروجی. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## ICUEncoding::GetBytes(const String\&) متد

بایت‌های حاصل از کدگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) برای کدگذاری. |

### مقدار بازگشت

[Buffer](../../../system/buffer/) که نمایانگر کاراکترهای کدگذاری شده را نگه می‌دارد.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int) متد

بایت‌های حاصل از کدگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | کاراکترهای برای کدگذاری. |
| index | int | شروع برش کاراکتر. |
| count | int | تعداد کاراکترهای قابل تبدیل. |

### مقدار بازگشت

[Buffer](../../../system/buffer/) که نمایانگر کاراکترهای کدگذاری شده را نگه می‌دارد.

## ICUEncoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) متد

بایت‌های حاصل از کدگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | کاراکترهای برای کدگذاری. |
| index | int | شروع برش کاراکتر. |
| count | int | تعداد کاراکترهای قابل تبدیل. |

### مقدار بازگشت

[Buffer](../../../system/buffer/) که نمایانگر کاراکترهای کدگذاری شده را نگه می‌دارد.

## ICUEncoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) متد

بایت‌های حاصل از کدگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | کاراکترهای برای کدگذاری. |
| index | int | شروع برش کاراکتر. |
| count | int | تعداد کاراکترهای قابل تبدیل. |

### مقدار بازگشت

[Buffer](../../../system/buffer/) که نمایانگر کاراکترهای کدگذاری شده را نگه می‌دارد.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>) متد

بایت‌های حاصل از کدگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | کاراکترهای برای کدگذاری. |

### مقدار بازگشت

[Buffer](../../../system/buffer/) که نمایانگر کاراکترهای کدگذاری شده را نگه می‌دارد.

## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) متد

بایت‌های حاصل از کدگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | const char_t * | کاراکترهای برای کدگذاری. |
| char_count | int | تعداد کاراکترهای قابل تبدیل. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها. |
| byte_count | int | اندازهٔ بافر خروجی. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## مراجع

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [ICUEncoding](../)
* کلاس [String](../../../system/string/)
* فضای نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)