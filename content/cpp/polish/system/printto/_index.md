---
title: PrintTo()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Wypisuje wartość do strumienia ostream. Najczęściej używane do debugowania.
type: docs
weight: 2146
url: /pl/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) function

Wypisuje wartość do strumienia ostream. Najczęściej używane do debugowania.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) function

Wypisuje wartość do strumienia ostream. Najczęściej używane do debugowania.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) function

Zapisuje wartość reprezentowaną przez określony obiekt do określonego strumienia wyjściowego.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | Obiekt [Decimal](../decimal/) do wypisania do strumienia |
| os | ::std::ostream * | Strumień, do którego ma zostać wypisany określony obiekt |

## System::PrintTo(const Details_Exception\&, std::ostream *) function

Wypisuje wartość do strumienia ostream. Najczęściej używane do debugowania.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) function

Wypisuje wartość do strumienia ostream. Najczęściej używane do debugowania.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) function

Wypisuje wartość do strumienia ostream. Najczęściej używane do debugowania.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) function

Wypisuje wartość do strumienia ostream. Najczęściej używane do debugowania.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) function

Wypisuje wartość do strumienia ostream. Najczęściej używane do debugowania.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) function

Wypisuje wartość do strumienia ostream. Najczęściej używane do debugowania.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) function

Wypisuje wartość do strumienia ostream. Najczęściej używane do debugowania.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) function

Wypisuje ciąg znaków do strumienia ostream. Najczęściej używane do debugowania.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [System::String](../string/)\& | do wypisania. |
| os | std::ostream * | docelowy ostream. |

## System::PrintTo(TimeSpan, std::ostream *) function

Wypisuje wartość do strumienia ostream. Najczęściej używane do debugowania.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) function

Wypisuje wartość do strumienia ostream. Najczęściej używane do debugowania.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## Zobacz także

* Klasa [DateTime](../datetime/)
* Klasa [DateTimeOffset](../datetimeoffset/)
* Klasa [Decimal](../decimal/)
* Klasa [Details_Exception](../details_exception/)
* Klasa [ExceptionWrapper](../exceptionwrapper/)
* Klasa [Guid](../guid/)
* Klasa [Nullable](../nullable/)
* Klasa [Object](../object/)
* Klasa [SmartPtr](../smartptr/)
* Klasa [String](../string/)
* Klasa [TimeSpan](../timespan/)
* Klasa [WeakPtr](../weakptr/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)