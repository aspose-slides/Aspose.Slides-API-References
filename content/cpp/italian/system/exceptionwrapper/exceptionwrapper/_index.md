---
title: ExceptionWrapper()
second_title: Riferimento API di Aspose.Slides per C++
description: Costruisce un'istanza nulla della classe ExceptionWrapper che non rappresenta alcuna eccezione.
type: docs
weight: 14
url: /it/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) costruttore

Crea un'istanza null della classe [ExceptionWrapper](../) che non rappresenta alcuna eccezione.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) costruttore

Crea un'istanza della classe [ExceptionWrapper](../) che contiene il puntatore passato.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | Puntatore intelligente all'istanza della classe Exception. |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) costruttore

Costruttore di copia.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | Altra istanza della classe wrapper che deve essere copiata. |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) costruttore

Costruttore di spostamento.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | Altra istanza della classe wrapper che deve essere spostata. |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) costruttore

Costruttore che inoltra i parametri ai costruttori della classe Exception e crea un puntatore intelligente che contiene una nuova istanza della classe Exception.

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## Vedi anche

* Typedef [ExceptionPtr](../../exceptionptr/)
* Classe [ExceptionWrapper](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)