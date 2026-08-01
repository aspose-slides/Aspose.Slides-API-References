---
title: PrintTo()
second_title: Aspose.Slides voor C++ API-referentie
description: Print de waarde naar ostream. Meestal gebruikt voor debug.
type: docs
weight: 2146
url: /nl/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) functie

Print de waarde naar ostream. Meestal gebruikt voor debug.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) functie

Print de waarde naar ostream. Meestal gebruikt voor debug.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) functie

Schrijft de waarde die wordt vertegenwoordigd door het opgegeven object naar de opgegeven uitvoerstream.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | Het [Decimal](../decimal/) object om naar de stream te printen |
| os | ::std::ostream * | De stream om het opgegeven object naar te printen |

## System::PrintTo(const Details_Exception\&, std::ostream *) functie

Print de waarde naar ostream. Meestal gebruikt voor debug.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) functie

Print de waarde naar ostream. Meestal gebruikt voor debug.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) functie

Print de waarde naar ostream. Meestal gebruikt voor debug.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) functie

Print de waarde naar ostream. Meestal gebruikt voor debug.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) functie

Print de waarde naar ostream. Meestal gebruikt voor debug.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) functie

Print de waarde naar ostream. Meestal gebruikt voor debug.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) functie

Print de waarde naar ostream. Meestal gebruikt voor debug.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) functie

Print de string naar ostream. Meestal gebruikt voor debug.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [System::String](../string/)\& | om te printen. |
| os | std::ostream * | doel ostream. |

## System::PrintTo(TimeSpan, std::ostream *) functie

Print de waarde naar ostream. Meestal gebruikt voor debug.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) functie

Print de waarde naar ostream. Meestal gebruikt voor debug.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## Zie ook

* Klasse [DateTime](../datetime/)
* Klasse [DateTimeOffset](../datetimeoffset/)
* Klasse [Decimal](../decimal/)
* Klasse [Details_Exception](../details_exception/)
* Klasse [ExceptionWrapper](../exceptionwrapper/)
* Klasse [Guid](../guid/)
* Klasse [Nullable](../nullable/)
* Klasse [Object](../object/)
* Klasse [SmartPtr](../smartptr/)
* Klasse [String](../string/)
* Klasse [TimeSpan](../timespan/)
* Klasse [WeakPtr](../weakptr/)
* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)