---
title: PrintTo()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Wert an den ostream aus. Wird hauptsächlich zum Debuggen verwendet.
type: docs
weight: 2146
url: /de/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) Funktion

Gibt den Wert an den ostream aus. Wird hauptsächlich zum Debuggen verwendet.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) Funktion

Gibt den Wert an den ostream aus. Wird hauptsächlich zum Debuggen verwendet.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) Funktion

Schreibt den von dem angegebenen Objekt dargestellten Wert in den angegebenen Ausgabestream.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | Das [Decimal](../decimal/) Objekt zum Ausgeben in den Stream |
| os | ::std::ostream * | Der Stream, in den das angegebene Objekt ausgegeben wird |

## System::PrintTo(const Details_Exception\&, std::ostream *) Funktion

Gibt den Wert an den ostream aus. Wird hauptsächlich zum Debuggen verwendet.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) Funktion

Gibt den Wert an den ostream aus. Wird hauptsächlich zum Debuggen verwendet.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) Funktion

Gibt den Wert an den ostream aus. Wird hauptsächlich zum Debuggen verwendet.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) Funktion

Gibt den Wert an den ostream aus. Wird hauptsächlich zum Debuggen verwendet.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) Funktion

Gibt den Wert an den ostream aus. Wird hauptsächlich zum Debuggen verwendet.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) Funktion

Gibt den Wert an den ostream aus. Wird hauptsächlich zum Debuggen verwendet.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) Funktion

Gibt den Wert an den ostream aus. Wird hauptsächlich zum Debuggen verwendet.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) Funktion

Gibt die Zeichenkette an den ostream aus. Wird hauptsächlich zum Debuggen verwendet.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [System::String](../string/)\& | zum Ausgeben. |
| os | std::ostream * | Ziel-ostream. |

## System::PrintTo(TimeSpan, std::ostream *) Funktion

Gibt den Wert an den ostream aus. Wird hauptsächlich zum Debuggen verwendet.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) Funktion

Gibt den Wert an den ostream aus. Wird hauptsächlich zum Debuggen verwendet.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## Siehe auch

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
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)