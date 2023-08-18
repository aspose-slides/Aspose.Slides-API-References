---
title: PrintTo()
second_title: Aspose.Slides for C++ API Reference
description: Prints value to ostream. Mostly used for debug.
type: docs
weight: 1977
url: /system/printto/
---
## System::PrintTo(DateTime, std::ostream *) function


Prints value to ostream. Mostly used for debug.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) function


Prints value to ostream. Mostly used for debug.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) function


Writes the value represented by the specified object to the specified output stream.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | The [Decimal](../decimal/) object to print to the stream |
| os | ::std::ostream * | The stream to print the specified object to |

## System::PrintTo(const Details_Exception\&, std::ostream *) function


Prints value to ostream. Mostly used for debug.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) function


Prints value to ostream. Mostly used for debug.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) function


Prints value to ostream. Mostly used for debug.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) function


Prints value to ostream. Mostly used for debug.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) function


Prints value to ostream. Mostly used for debug.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) function


Prints value to ostream. Mostly used for debug.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) function


Prints value to ostream. Mostly used for debug.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) function


Prints string to ostream. Mostly used for debug.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::String](../string/)\& | to print. |
| os | std::ostream * | target ostream. |

## System::PrintTo(TimeSpan, std::ostream *) function


Prints value to ostream. Mostly used for debug.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) function


Prints value to ostream. Mostly used for debug.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## See Also

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