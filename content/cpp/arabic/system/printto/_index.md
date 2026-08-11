---
title: PrintTo()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يطبع القيمة إلى ostream. يُستخدم في الغالب للتصحيح.
type: docs
weight: 2146
url: /ar/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) دالة

يطبع القيمة إلى ostream. يُستخدم في الغالب للتصحيح.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) دالة

يطبع القيمة إلى ostream. يُستخدم في الغالب للتصحيح.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) دالة

يكتب القيمة التي يمثلها الكائن المحدد إلى تدفق الإخراج المحدد.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | كائن [Decimal](../decimal/) للطباعة إلى الدفق |
| os | ::std::ostream * | الدفق لطباعة الكائن المحدد إليه |

## System::PrintTo(const Details_Exception\&, std::ostream *) دالة

يطبع القيمة إلى ostream. يُستخدم في الغالب للتصحيح.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) دالة

يطبع القيمة إلى ostream. يُستخدم في الغالب للتصحيح.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) دالة

يطبع القيمة إلى ostream. يُستخدم في الغالب للتصحيح.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) دالة

يطبع القيمة إلى ostream. يُستخدم في الغالب للتصحيح.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) دالة

يطبع القيمة إلى ostream. يُستخدم في الغالب للتصحيح.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) دالة

يطبع القيمة إلى ostream. يُستخدم في الغالب للتصحيح.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) دالة

يطبع القيمة إلى ostream. يُستخدم في الغالب للتصحيح.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) دالة

يطبع النص إلى ostream. يُستخدم في الغالب للتصحيح.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::String](../string/)\& | للطباعة. |
| os | std::ostream * | ostream الهدف. |

## System::PrintTo(TimeSpan, std::ostream *) دالة

يطبع القيمة إلى ostream. يُستخدم في الغالب للتصحيح.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) دالة

يطبع القيمة إلى ostream. يُستخدم في الغالب للتصحيح.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## See Also

* الفئة [DateTime](../datetime/)
* الفئة [DateTimeOffset](../datetimeoffset/)
* الفئة [Decimal](../decimal/)
* الفئة [Details_Exception](../details_exception/)
* الفئة [ExceptionWrapper](../exceptionwrapper/)
* الفئة [Guid](../guid/)
* الفئة [Nullable](../nullable/)
* الفئة [Object](../object/)
* الفئة [SmartPtr](../smartptr/)
* الفئة [String](../string/)
* الفئة [TimeSpan](../timespan/)
* الفئة [WeakPtr](../weakptr/)
* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)