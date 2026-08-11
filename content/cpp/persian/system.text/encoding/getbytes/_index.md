---
title: GetBytes()
second_title: مرجع API Aspose.Slides برای C++
description: بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند.
type: docs
weight: 248
url: /fa/system.text/encoding/getbytes/
---
## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) متد

بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | کاراکترهای قابل رمزگذاری. |
| char_index | int | شروع برش کاراکتر. |
| char_count | int | تعداد کاراکترهای برای تبدیل. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها. |
| byte_index | int | افست بافر خروجی. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) متد

بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | کاراکترهای قابل رمزگذاری. |
| char_index | int | شروع برش کاراکتر. |
| char_count | int | تعداد کاراکترهای برای تبدیل. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها. |
| byte_index | int | افست بافر خروجی. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) متد

بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | کاراکترهای قابل رمزگذاری. |
| char_index | int | شروع برش کاراکتر. |
| char_count | int | تعداد کاراکترهای برای تبدیل. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها. |
| byte_index | int | افست بافر خروجی. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) متد

بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) برای رمزگذاری. |
| char_index | int | شروع برش کاراکتر. |
| char_count | int | تعداد کاراکترهای برای تبدیل. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها. |
| byte_index | int | افست بافر خروجی. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## Encoding::GetBytes(const String\&) متد

بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) برای رمزگذاری. |

### مقدار بازگشت

[Buffer](../../../system/buffer/) که نمایانگر کاراکترهای رمزگذاری‌شده را دارد.

## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) متد

بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | کاراکترهای قابل رمزگذاری. |
| index | int | شروع برش کاراکتر. |
| count | int | تعداد کاراکترهای برای تبدیل. |

### مقدار بازگشت

[Buffer](../../../system/buffer/) که نمایانگر کاراکترهای رمزگذاری‌شده را دارد.

## Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) متد

بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | کاراکترهای قابل رمزگذاری. |
| index | int | شروع برش کاراکتر. |
| count | int | تعداد کاراکترهای برای تبدیل. |

### مقدار بازگشت

[Buffer](../../../system/buffer/) که نمایانگر کاراکترهای رمزگذاری‌شده را دارد.

## Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) متد

بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | کاراکترهای قابل رمزگذاری. |
| index | int | شروع برش کاراکتر. |
| count | int | تعداد کاراکترهای برای تبدیل. |

### مقدار بازگشت

[Buffer](../../../system/buffer/) که نمایانگر کاراکترهای رمزگذاری‌شده را دارد.

## Encoding::GetBytes(ArrayPtr\<char_t\>) متد

بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | کاراکترهای قابل رمزگذاری. |

### مقدار بازگشت

[Buffer](../../../system/buffer/) که نمایانگر کاراکترهای رمزگذاری‌شده را دارد.

## Encoding::GetBytes(const char_t *, int, uint8_t *, int) متد

بایت‌های حاصل از رمزگذاری یک بافر کاراکتر را دریافت می‌کند.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | کاراکترهای قابل رمزگذاری. |
| char_count | int | تعداد کاراکترهای برای تبدیل. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها. |
| byte_count | int | اندازه بافر خروجی. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## موارد مرتبط

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [Encoding](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)