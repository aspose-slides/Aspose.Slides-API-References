---
title: PrintTo()
second_title: Riferimento API Aspose.Slides per C++
description: Stampa il valore su ostream. Usato principalmente per debug.
type: docs
weight: 2146
url: /it/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) funzione

Stampa il valore su ostream. Usato principalmente per debug.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) funzione

Stampa il valore su ostream. Usato principalmente per debug.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) funzione

Scrive il valore rappresentato dall'oggetto specificato sullo stream di output specificato.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | L'oggetto [Decimal](../decimal/) da stampare sullo stream |
| os | ::std::ostream * | Lo stream su cui stampare l'oggetto specificato |

## System::PrintTo(const Details_Exception\&, std::ostream *) funzione

Stampa il valore su ostream. Usato principalmente per debug.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) funzione

Stampa il valore su ostream. Usato principalmente per debug.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) funzione

Stampa il valore su ostream. Usato principalmente per debug.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) funzione

Stampa il valore su ostream. Usato principalmente per debug.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) funzione

Stampa il valore su ostream. Usato principalmente per debug.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) funzione

Stampa il valore su ostream. Usato principalmente per debug.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) funzione

Stampa il valore su ostream. Usato principalmente per debug.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) funzione

Stampa la stringa su ostream. Usato principalmente per debug.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [System::String](../string/)\& | da stampare. |
| os | std::ostream * | ostream di destinazione. |

## System::PrintTo(TimeSpan, std::ostream *) funzione

Stampa il valore su ostream. Usato principalmente per debug.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) funzione

Stampa il valore su ostream. Usato principalmente per debug.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## Vedi anche

* Classe [DateTime](../datetime/)
* Classe [DateTimeOffset](../datetimeoffset/)
* Classe [Decimal](../decimal/)
* Classe [Details_Exception](../details_exception/)
* Classe [ExceptionWrapper](../exceptionwrapper/)
* Classe [Guid](../guid/)
* Classe [Nullable](../nullable/)
* Classe [Object](../object/)
* Classe [SmartPtr](../smartptr/)
* Classe [String](../string/)
* Classe [TimeSpan](../timespan/)
* Classe [WeakPtr](../weakptr/)
* Namespace [System](../)
* Libreria [Aspose.Slides](../../)