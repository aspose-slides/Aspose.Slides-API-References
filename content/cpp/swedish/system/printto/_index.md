---
title: PrintTo()
second_title: Aspose.Slides för C++ API-referens
description: Skriver värdet till ostream. Används främst för felsökning.
type: docs
weight: 2146
url: /sv/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) funktion


Skriver värdet till ostream. Används främst för felsökning.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) funktion


Skriver värdet till ostream. Används främst för felsökning.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) funktion


Skriver det värde som representeras av det angivna objektet till den angivna utmatningsströmmen.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | Det [Decimal](../decimal/)-objektet som ska skrivas till strömmen |
| os | ::std::ostream * | Strömmen som det angivna objektet ska skrivas till |

## System::PrintTo(const Details_Exception\&, std::ostream *) funktion


Skriver värdet till ostream. Används främst för felsökning.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) funktion


Skriver värdet till ostream. Används främst för felsökning.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) funktion


Skriver värdet till ostream. Används främst för felsökning.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) funktion


Skriver värdet till ostream. Används främst för felsökning.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) funktion


Skriver värdet till ostream. Används främst för felsökning.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) funktion


Skriver värdet till ostream. Används främst för felsökning.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) funktion


Skriver värdet till ostream. Används främst för felsökning.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) funktion


Skriver strängen till ostream. Används främst för felsökning.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [System::String](../string/)\& | att skriva. |
| os | std::ostream * | mål-ostream. |

## System::PrintTo(TimeSpan, std::ostream *) funktion


Skriver värdet till ostream. Används främst för felsökning.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) funktion


Skriver värdet till ostream. Används främst för felsökning.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## Se även

* Klass [DateTime](../datetime/)
* Klass [DateTimeOffset](../datetimeoffset/)
* Klass [Decimal](../decimal/)
* Klass [Details_Exception](../details_exception/)
* Klass [ExceptionWrapper](../exceptionwrapper/)
* Klass [Guid](../guid/)
* Klass [Nullable](../nullable/)
* Klass [Object](../object/)
* Klass [SmartPtr](../smartptr/)
* Klass [String](../string/)
* Klass [TimeSpan](../timespan/)
* Klass [WeakPtr](../weakptr/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)