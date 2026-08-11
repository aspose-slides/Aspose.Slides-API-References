---
title: String()
second_title: Aspose.Slides برای C++ مرجع API
description: سازنده پیش‌فرض. یک شیء رشته ایجاد می‌کند که به عنوان تهی در نظر گرفته می‌شود.
type: docs
weight: 14
url: /fa/system/string/string/
---
## String::String() سازنده

سازنده پیش‌فرض. یک شیء رشته ایجاد می‌کند که به عنوان تهی در نظر گرفته می‌شود.

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) سازنده

رشته را بر پایه‌ی رشتهٔ ثابت می‌سازد. ثابت را به‌عنوان رشته‌ای با انتهای null درنظر می‌گیرد و طول رشته هدف را بر پایه‌ی اندازهٔ ثابت محاسبه می‌کند.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | T\& | [String](../) اشاره‌گر ثابت. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) سازنده

رشته را بر پایه‌ی اشاره‌گر به رشتهٔ کاراکتری می‌سازد. رشتهٔ اشاره‌شده را به‌عنوان رشته‌ای با انتهای null درنظر می‌گیرد و طول رشته هدف را بر پایه‌ی کاراکتر null محاسبه می‌کند.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const T\& | اشاره‌گر به رشتهٔ کاراکتری. |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) سازنده

رشته را بر پایه‌ی رشتهٔ ثابت می‌سازد. ثابت را به‌عنوان رشته‌ای با انتهای null در UTF8 درنظر می‌گیرد و طول رشته هدف را بر پایه‌ی اندازهٔ ثابت محاسبه می‌کند.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | T\& | [String](../) اشاره‌گر ثابت. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) سازنده

رشته را بر پایه‌ی اشاره‌گر به رشتهٔ کاراکتری می‌سازد. رشتهٔ اشاره‌شده را در UTF8 به‌عنوان رشته‌ای با انتهای null درنظر می‌گیرد و طول رشته هدف را بر پایه‌ی کاراکتر null محاسبه می‌کند.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const T\& | اشاره‌گر به رشتهٔ کاراکتری. |

## String::String(const char16_t *, int) سازنده

رشته را از اشاره‌گر به رشتهٔ کاراکتری و طول صریح می‌سازد.

```cpp
System::String::String(const char16_t *str, int length)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const char16_t * | [String](../) اشاره‌گر، ممکن است ثابت یا آرایه باشد. |
| length | int | طول صریح رشته |

## String::String(const ReadOnlySpan\<char16_t\>\&) سازنده

یک نمونه جدید از کلاس [System.String](../) را با کاراکترهای یونیکد مشخص‌شده در بازهٔ فقط-خواندنی داده‌شده مقداردهی اولیه می‌کند.

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | یک بازهٔ فقط-خواندنی از کاراکترهای یونیکد. |

## String::String(const char *, int) سازنده

رشته را از اشاره‌گر به کاراکترهای UTF8 و طول صریح می‌سازد.

```cpp
System::String::String(const char *str, int length)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const char * | [String](../) اشاره‌گر به داده‌های UTF8، ممکن است ثابت یا آرایه باشد. |
| length | int | طول صریح رشته |

## String::String(const char16_t *, int, int) سازنده

رشته را از اشاره‌گر به رشتهٔ کاراکتری، از موقعیت شروع با استفاده از طول می‌سازد.

```cpp
System::String::String(const char16_t *str, int start, int length)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const char16_t * | [String](../) اشاره‌گر، ممکن است ثابت یا آرایه باشد. |
| start | int | موقعیت شروع. |
| length | int | [String](../) طول. |

## String::String(const char16_t, int) سازنده

سازنده پرکننده.

```cpp
System::String::String(const char16_t ch, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ch | const char16_t | کاراکتر پرکننده. |
| count | int | طول هدف. |

## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) سازنده

سازنده nullptr. به‌عنوان قالب اعلام شده است تا اولویت‌ها با سایر سازنده‌های قالبی حل شود.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | باید nullptr_t باشد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) سازنده

رشته را بر پایه‌ی ثابت widestring می‌سازد. ثابت را به‌عنوان رشته‌ای با انتهای null درنظر می‌گیرد و طول رشته هدف را بر پایه‌ی اندازهٔ ثابت محاسبه می‌کند. تبدیل از **wchar_t** در برخی سکوها زمان‌بر است، بنابراین تبدیل‌های ضمنی مجاز نیستند.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | T\& | [String](../) اشاره‌گر ثابت. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) سازنده

رشته را بر پایه‌ی اشاره‌گر به رشتهٔ کاراکتری (widecharacter) می‌سازد. رشتهٔ اشاره‌شده را به‌عنوان رشته‌ای با انتهای null درنظر می‌گیرد و طول رشته هدف را بر پایه‌ی کاراکتر null محاسبه می‌کند. تبدیل از **wchar_t** در برخی سکوها زمان‌بر است، بنابراین تبدیل‌های ضمنی مجاز نیستند.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const T\& | اشاره‌گر به رشتهٔ کاراکتری. |

## String::String(const wchar_t *, int) سازنده

رشته را از اشاره‌گر به widecharacter و طول صریح می‌سازد. تبدیل از **wchar_t** در برخی سکوها زمان‌بر است، بنابراین تبدیل‌های ضمنی مجاز نیستند.

```cpp
System::String::String(const wchar_t *str, int length)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) اشاره‌گر، ممکن است ثابت یا آرایه باشد. |
| length | int | طول صریح رشته |

## String::String(const wchar_t, int) سازنده

سازنده پرکننده. تبدیل از **wchar_t** در برخی سکوها زمان‌بر است، بنابراین تبدیل‌های ضمنی مجاز نیستند.

```cpp
System::String::String(const wchar_t ch, int count=1)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ch | const **wchar_t** | کاراکتر پرکننده. |
| count | int | طول هدف. |

## String::String(const String\&) سازنده

سازندهٔ کپی.

```cpp
System::String::String(const String &str)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) برای کپی. |

## String::String(String\&&) سازنده

سازندهٔ جابجایی.

```cpp
System::String::String(String &&str) noexcept
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) برای جابجایی داده‌ها از. |

## String::String(const ArrayPtr\<char16_t\>\&) سازنده

کل آرایهٔ کاراکتری را به رشته تبدیل می‌کند.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) برای تبدیل به رشته. |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) سازنده

بخش زیرمجموعه‌ای از آرایهٔ کاراکتری را به رشته تبدیل می‌کند. اگر پارامترها خارج از محدوده آرایه باشند، رشتهٔ خالی ساخته می‌شود.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | آرایهٔ کاراکتری. |
| offset | int | اندیس شروع زیرآرایه. |
| len | int | طول زیرآرایه. |

## String::String(const codeporting_icu::UnicodeString\&) سازنده

UnicodeString را در [String](../) می‌پیچد.

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString برای پیچیدن در [String](../). |

## String::String(codeporting_icu::UnicodeString\&&) سازنده

سازندهٔ جابجایی.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString برای پیچیدن در [String](../). |

## String::String(const std::wstring\&) سازنده

[String](../) را از widestring ایجاد می‌کند.

```cpp
System::String::String(const std::wstring &str)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const std::wstring\& | widestring برای تبدیل به [String](../). |

## String::String(const std::u16string\&) سازنده

[String](../) را از رشتهٔ utf16 ایجاد می‌کند.

```cpp
System::String::String(const std::u16string &str)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const std::u16string\& | رشتهٔ Utf16 برای تبدیل به [String](../). |

## String::String(const std::string\&) سازنده

[String](../) را از رشتهٔ std::string که در قالب UTF-8 ارائه شده است ایجاد می‌کند.

```cpp
System::String::String(const std::string &utf8str)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| utf8str | const std::string\& | رشتهٔ std::string برای تبدیل به [String](../). |

## String::String(const std::u32string\&) سازنده

[String](../) را از رشتهٔ std::u32string ایجاد می‌کند.

```cpp
System::String::String(const std::u32string &u32str)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| u32str | const std::u32string\& | رشتهٔ std::u32string برای تبدیل به [String](../). |

## مراجع

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Class [ReadOnlySpan](../../readonlyspan/)
* Struct [IsStringLiteral](../../isstringliteral/)
* Struct [IsStringPointer](../../isstringpointer/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)