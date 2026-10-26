---
title: Format()
second_title: مرجع API Aspose.Slides برای C++
description: رشته را به سبک C# فرمت می‌کند.
type: docs
weight: 885
url: /fa/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) method

رشته را به سبک C# فرمت می‌کند.

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Args | آرگومان‌ها برای فرمت‌کردن رشته. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ارائه‌دهنده قالب برای استفاده برای تبدیل آرگومان‌ها به رشته‌ها. |
| format | const [String](../)\& | رشته قالب. |
| args | const Args\&... | آرگومان‌ها برای فرمت‌کردن رشته. |

## String::Format(std::nullptr_t, const String\&, const Args\&...) method

رشته را به سبک C# فرمت می‌کند.

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Args | آرگومان‌ها برای فرمت‌کردن رشته. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| format | std::nullptr_t | رشته قالب. |
| args | const [String](../)\& | آرگومان‌ها برای فرمت‌کردن رشته. |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) method

رشته را به سبک C# فرمت می‌کند.

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Args | آرگومان‌ها برای فرمت‌کردن رشته. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| format | std::nullptr_t | رشته قالب. |
| args | const char16_t(&) | آرگومان‌ها برای فرمت‌کردن رشته. |

## String::Format(const String\&, const Args\&...) method

رشته را به سبک C# فرمت می‌کند.

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Args | آرگومان‌ها برای فرمت‌کردن رشته. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| format | const [String](../)\& | رشته قالب. |
| args | const Args\&... | آرگومان‌ها برای فرمت‌کردن رشته. |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) method

رشته را به سبک C# فرمت می‌کند.

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | آرگومان‌ها برای فرمت‌کردن رشته. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| format | const [String](../)\& | رشته قالب. |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | آرگومان‌ها برای فرمت‌کردن رشته. |

## همچنین ببینید

* نوع‌تعریف [SharedPtr](../../sharedptr/)
* نوع‌تعریف [ArrayPtr](../../arrayptr/)
* کلاس [String](../)
* کلاس [IFormatProvider](../../iformatprovider/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)