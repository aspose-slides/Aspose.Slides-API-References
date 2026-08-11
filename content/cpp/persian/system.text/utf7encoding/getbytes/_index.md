---
title: GetBytes()
second_title: Aspose.Slides برای C++ مرجع API
description: بایت‌هایی که از رمزگذاری یک بافر کاراکتر به دست می‌آید.
type: docs
weight: 66
url: /fa/system.text/utf7encoding/getbytes/
---
## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) متد

بایت‌هایی که از رمزگذاری یک بافر کاراکتر به دست می‌آید را دریافت کنید.

```cpp
int System::Text::UTF7Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | کاراکترهایی که باید رمزگذاری شوند. |
| char_index | int | شروع قطعه کاراکتر. |
| char_count | int | تعداد کاراکترهایی که باید تبدیل شوند. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها. |
| byte_index | int | موقعیت بافر خروجی. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) متد

بایت‌هایی که از رمزگذاری یک بافر کاراکتر به دست می‌آید را دریافت کنید.

```cpp
int System::Text::UTF7Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | const char_t * | کاراکترهایی که باید رمزگذاری شوند. |
| char_count | int | تعداد کاراکترهایی که باید تبدیل شوند. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها. |
| byte_count | int | اندازه بافر خروجی. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) متد

بایت‌هایی که از رمزگذاری یک بافر کاراکتر به دست می‌آید را دریافت کنید.

```cpp
int System::Text::UTF7Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) برای رمزگذاری. |
| char_index | int | شروع قطعه کاراکتر. |
| char_count | int | تعداد کاراکترهایی که باید تبدیل شوند. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها. |
| byte_index | int | موقعیت بافر خروجی. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) متد

بایت‌هایی که از رمزگذاری یک بافر کاراکتر به دست می‌آید را دریافت کنید.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | کاراکترهایی که باید رمزگذاری شوند. |
| char_index | int | شروع قطعه کاراکتر. |
| char_count | int | تعداد کاراکترهایی که باید تبدیل شوند. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها. |
| byte_index | int | موقعیت بافر خروجی. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## UTF7Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) متد

بایت‌هایی که از رمزگذاری یک بافر کاراکتر به دست می‌آید را دریافت کنید.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | کاراکترهایی که باید رمزگذاری شوند. |
| char_index | int | شروع قطعه کاراکتر. |
| char_count | int | تعداد کاراکترهایی که باید تبدیل شوند. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها. |
| byte_index | int | موقعیت بافر خروجی. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## UTF7Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) متد

بایت‌هایی که از رمزگذاری یک بافر کاراکتر به دست می‌آید را دریافت کنید.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | کاراکترهایی که باید رمزگذاری شوند. |
| char_index | int | شروع قطعه کاراکتر. |
| char_count | int | تعداد کاراکترهایی که باید تبدیل شوند. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها. |
| byte_index | int | موقعیت بافر خروجی. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) متد

بایت‌هایی که از رمزگذاری یک بافر کاراکتر به دست می‌آید را دریافت کنید.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) برای رمزگذاری. |
| char_index | int | شروع قطعه کاراکتر. |
| char_count | int | تعداد کاراکترهایی که باید تبدیل شوند. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها. |
| byte_index | int | موقعیت بافر خروجی. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## UTF7Encoding::GetBytes(const String\&) متد

بایت‌هایی که از رمزگذاری یک بافر کاراکتر به دست می‌آید را دریافت کنید.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) برای رمزگذاری. |

### مقدار بازگشت

[Buffer](../../../system/buffer/) که نمایی از کاراکترهای رمزگذاری‌شده را نگه می‌دارد.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) متد

بایت‌هایی که از رمزگذاری یک بافر کاراکتر به دست می‌آید را دریافت کنید.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | کاراکترهایی که باید رمزگذاری شوند. |
| index | int | شروع قطعه کاراکتر. |
| count | int | تعداد کاراکترهایی که باید تبدیل شوند. |

### مقدار بازگشت

[Buffer](../../../system/buffer/) که نمایی از کاراکترهای رمزگذاری‌شده را نگه می‌دارد.

## UTF7Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) متد

بایت‌هایی که از رمزگذاری یک بافر کاراکتر به دست می‌آید را دریافت کنید.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | کاراکترهایی که باید رمزگذاری شوند. |
| index | int | شروع قطعه کاراکتر. |
| count | int | تعداد کاراکترهایی که باید تبدیل شوند. |

### مقدار بازگشت

[Buffer](../../../system/buffer/) که نمایی از کاراکترهای رمزگذاری‌شده را نگه می‌دارد.

## UTF7Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) متد

بایت‌هایی که از رمزگذاری یک بافر کاراکتر به دست می‌آید را دریافت کنید.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | کاراکترهایی که باید رمزگذاری شوند. |
| index | int | شروع قطعه کاراکتر. |
| count | int | تعداد کاراکترهایی که باید تبدیل شوند. |

### مقدار بازگشت

[Buffer](../../../system/buffer/) که نمایی از کاراکترهای رمزگذاری‌شده را نگه می‌دارد.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>) متد

بایت‌هایی که از رمزگذاری یک بافر کاراکتر به دست می‌آید را دریافت کنید.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | کاراکترهایی که باید رمزگذاری شوند. |

### مقدار بازگشت

[Buffer](../../../system/buffer/) که نمایی از کاراکترهای رمزگذاری‌شده را نگه می‌دارد.

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) متد

بایت‌هایی که از رمزگذاری یک بافر کاراکتر به دست می‌آید را دریافت کنید.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | const char_t * | کاراکترهایی که باید رمزگذاری شوند. |
| char_count | int | تعداد کاراکترهایی که باید تبدیل شوند. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) برای قرار دادن کاراکترها. |
| byte_count | int | اندازه بافر خروجی. |

### مقدار بازگشت

تعداد بایت‌های نوشته‌شده.

## همچنین ببینید

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)