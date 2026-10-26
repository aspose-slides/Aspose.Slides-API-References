---
title: Concat()
second_title: Aspose.Slides برای C++ API مرجع
description: آرایهٔ رشته‌ها را ترکیب می‌کند.
type: docs
weight: 1
url: /fa/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) function


رشته‌های آرایه را ترکیب می‌کند.

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) از رشته‌ها برای ترکیب. |

### Return Value

رشتهٔ ترکیب‌شده.

## System::StringExtra::Concat(const String\&, const String\&) function


رشته‌ها را ترکیب می‌کند.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | رشتهٔ اول برای ترکیب. |
| str1 | const [String](../../system/string/)\& | رشتهٔ دوم برای ترکیب. |

### Return Value

رشته‌های پارامتر ترکیب‌شده.

## System::StringExtra::Concat(const String\&, const String\&, const String\&) function


رشته‌ها را ترکیب می‌کند.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | رشتهٔ اول برای ترکیب. |
| str1 | const [String](../../system/string/)\& | رشتهٔ دوم برای ترکیب. |
| str2 | const [String](../../system/string/)\& | رشتهٔ سوم برای ترکیب. |

### Return Value

رشته‌های پارامتر ترکیب‌شده.

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) function


رشته‌ها را ترکیب می‌کند.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | رشتهٔ اول برای ترکیب. |
| str1 | const [String](../../system/string/)\& | رشتهٔ دوم برای ترکیب. |
| str2 | const [String](../../system/string/)\& | رشتهٔ سوم برای ترکیب. |
| str3 | const [String](../../system/string/)\& | رشتهٔ چهارم برای ترکیب. |

### Return Value

رشته‌های پارامتر ترکیب‌شده.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) function


چندین شیء را به رشته تبدیل می‌کند و رشته‌های حاصل را ترکیب می‌نماید. تخصص برای [SmartPtr](../../system/smartptr/) types.

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) برای تبدیل و ترکیب. |

### Return Value

مقدار [String](../../system/string/) ترکیب‌شده از نمایش‌های رشته‌ای تمام اشیاء عبور داده‌شده.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) function


چندین شیء را به رشته تبدیل می‌کند و رشته‌های حاصل را ترکیب می‌نماید. تخصص برای arithmetic types.

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) برای تبدیل و ترکیب. |

### Return Value

مقدار [String](../../system/string/) ترکیب‌شده از نمایش‌های رشته‌ای تمام اشیاء عبور داده‌شده.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) function


چندین شیء را به رشته تبدیل می‌کند و رشته‌های حاصل را ترکیب می‌نماید. تخصص برای structures and other value types.

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) برای تبدیل و ترکیب. |

### Return Value

مقدار [String](../../system/string/) ترکیب‌شده از نمایش‌های رشته‌ای تمام اشیاء عبور داده‌شده.

## See Also

* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [String](../../system/string/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::StringExtra](../)
* Library [Aspose.Slides](../../)