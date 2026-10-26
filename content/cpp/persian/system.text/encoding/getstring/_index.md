---
title: GetString()
second_title: مرجع API Aspose.Slides برای C++
description: یک بافر از بایت‌ها را به رشته‌ای رمزگشایی می‌کند.
type: docs
weight: 313
url: /fa/system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) متد

یک بافر از بایت‌ها را به یک رشته تبدیل می‌کند.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |
| byte_count | int | اندازهٔ بافر ورودی. |

### مقدار بازگشت

[String](../../../system/string/) از کاراکترهای رمزگشایی شده.

## Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) متد

یک بافر از بایت‌ها را به یک رشته تبدیل می‌کند.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |

### مقدار بازگشت

[String](../../../system/string/) از کاراکترهای رمزگشایی شده.

## Encoding::GetString(ArrayPtr\<uint8_t\>) متد

یک بافر از بایت‌ها را به یک رشته تبدیل می‌کند.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |

### مقدار بازگشت

[String](../../../system/string/) از کاراکترهای رمزگشایی شده.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) متد

یک بافر از بایت‌ها را به یک رشته تبدیل می‌کند.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |

### مقدار بازگشت

[String](../../../system/string/) از کاراکترهای رمزگشایی شده.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) متد

یک بافر از بایت‌ها را به یک رشته تبدیل می‌کند.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |

### مقدار بازگشت

[String](../../../system/string/) از کاراکترهای رمزگشایی شده.

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) متد

یک بافر از بایت‌ها را به یک رشته تبدیل می‌کند.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |
| index | int | جابجایی بافر ورودی. |
| count | int | اندازهٔ بافر ورودی. |

### مقدار بازگشت

[String](../../../system/string/) از کاراکترهای رمزگشایی شده.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) متد

یک بافر از بایت‌ها را به یک رشته تبدیل می‌کند.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |
| index | int | جابجایی بافر ورودی. |
| count | int | اندازهٔ بافر ورودی. |

### مقدار بازگشت

[String](../../../system/string/) از کاراکترهای رمزگشایی شده.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) متد

یک بافر از بایت‌ها را به یک رشته تبدیل می‌کند.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) برای خواندن بایت‌ها از. |
| index | int | جابجایی بافر ورودی. |
| count | int | اندازهٔ بافر ورودی. |

### مقدار بازگشت

[String](../../../system/string/) از کاراکترهای رمزگشایی شده.

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [String](../../../system/string/)
* کلاس [Encoding](../)
* کلاس [ReadOnlySpan](../../../system/readonlyspan/)
* فضای‌نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)