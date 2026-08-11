---
title: PrintTo()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار را به ostream می‌نویسد. عمدتاً برای اشکال‌زدایی استفاده می‌شود.
type: docs
weight: 2146
url: /fa/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) تابع

مقدار را به ostream می‌نویسد. عمدتاً برای اشکال‌زدایی استفاده می‌شود.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) تابع

مقدار را به ostream می‌نویسد. عمدتاً برای اشکال‌زدایی استفاده می‌شود.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) تابع

مقدار نمایندهٔ شیء مشخص شده را به جریان خروجی مشخص‌شده می‌نویسد.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | شیء [Decimal](../decimal/) برای چاپ به جریان |
| os | ::std::ostream * | جریان برای چاپ شیء مشخص‌شده |

## System::PrintTo(const Details_Exception\&, std::ostream *) تابع

مقدار را به ostream می‌نویسد. عمدتاً برای اشکال‌زدایی استفاده می‌شود.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) تابع

مقدار را به ostream می‌نویسد. عمدتاً برای اشکال‌زدایی استفاده می‌شود.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) تابع

مقدار را به ostream می‌نویسد. عمدتاً برای اشکال‌زدایی استفاده می‌شود.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) تابع

مقدار را به ostream می‌نویسد. عمدتاً برای اشکال‌زدایی استفاده می‌شود.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) تابع

مقدار را به ostream می‌نویسد. عمدتاً برای اشکال‌زدایی استفاده می‌شود.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) تابع

مقدار را به ostream می‌نویسد. عمدتاً برای اشکال‌زدایی استفاده می‌شود.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) تابع

مقدار را به ostream می‌نویسد. عمدتاً برای اشکال‌زدایی استفاده می‌شود.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) تابع

رشته را به ostream می‌نویسد. عمدتاً برای اشکال‌زدایی استفاده می‌شود.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [System::String](../string/)\& | برای چاپ. |
| os | std::ostream * | ostream هدف. |

## System::PrintTo(TimeSpan, std::ostream *) تابع

مقدار را به ostream می‌نویسد. عمدتاً برای اشکال‌زدایی استفاده می‌شود.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) تابع

مقدار را به ostream می‌نویسد. عمدتاً برای اشکال‌زدایی استفاده می‌شود.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## مراجع

* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Decimal](../decimal/)
* Class [Details_Exception](../details_exception/)
* Class [ExceptionWrapper](../exceptionwrapper/)
* Class [Guid](../guid/)
* Class [Nullable](../nullable/)
* Class [Object](../object/)
* Class [SmartPtr](../smartptr/)
* Class [String](../string/)
* Class [TimeSpan](../timespan/)
* Class [WeakPtr](../weakptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)