---
title: PrintTo()
second_title: Aspose.Slides pro C++ API Reference
description: Vytiskne hodnotu do ostream. Většinou se používá pro ladění.
type: docs
weight: 2146
url: /cs/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) funkce


Vytiskne hodnotu do ostream. Většinou se používá pro ladění.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) funkce


Vytiskne hodnotu do ostream. Většinou se používá pro ladění.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) funkce


Zapíše hodnotu reprezentovanou zadaným objektem do zadaného výstupního proudu.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | Objekt [Decimal](../decimal/) k vytištění do proudu |
| os | ::std::ostream * | Proud, do kterého se má vytisknout zadaný objekt |

## System::PrintTo(const Details_Exception\&, std::ostream *) funkce


Vytiskne hodnotu do ostream. Většinou se používá pro ladění.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) funkce


Vytiskne hodnotu do ostream. Většinou se používá pro ladění.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) funkce


Vytiskne hodnotu do ostream. Většinou se používá pro ladění.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) funkce


Vytiskne hodnotu do ostream. Většinou se používá pro ladění.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) funkce


Vytiskne hodnotu do ostream. Většinou se používá pro ladění.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) funkce


Vytiskne hodnotu do ostream. Většinou se používá pro ladění.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) funkce


Vytiskne hodnotu do ostream. Většinou se používá pro ladění.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) funkce


Vytiskne řetězec do ostream. Většinou se používá pro ladění.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [System::String](../string/)\& | k vytištění. |
| os | std::ostream * | cíl ostream. |

## System::PrintTo(TimeSpan, std::ostream *) funkce


Vytiskne hodnotu do ostream. Většinou se používá pro ladění.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) funkce


Vytiskne hodnotu do ostream. Většinou se používá pro ladění.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## Viz také

* Třída [DateTime](../datetime/)
* Třída [DateTimeOffset](../datetimeoffset/)
* Třída [Decimal](../decimal/)
* Třída [Details_Exception](../details_exception/)
* Třída [ExceptionWrapper](../exceptionwrapper/)
* Třída [Guid](../guid/)
* Třída [Nullable](../nullable/)
* Třída [Object](../object/)
* Třída [SmartPtr](../smartptr/)
* Třída [String](../string/)
* Třída [TimeSpan](../timespan/)
* Třída [WeakPtr](../weakptr/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)