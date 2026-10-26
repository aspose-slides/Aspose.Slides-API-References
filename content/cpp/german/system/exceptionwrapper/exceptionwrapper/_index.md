---
title: ExceptionWrapper()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine Null-Instanz der Klasse ExceptionWrapper, die keine Ausnahme darstellt.
type: docs
weight: 14
url: /de/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) Konstruktor

Erstellt eine Null-Instanz der Klasse [ExceptionWrapper](../), die keine Ausnahme darstellt.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) Konstruktor

Erstellt eine Instanz der Klasse [ExceptionWrapper](../), die den übergebenen Zeiger enthält.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | Smart-Pointer auf die Instanz der Klasse Exception. |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) Konstruktor

Kopierkonstruktor.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | Andere Instanz der Wrapper-Klasse, die kopiert werden muss. |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) Konstruktor

Move-Konstruktor.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | Andere Instanz der Wrapper-Klasse, die verschoben werden muss. |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) Konstruktor

Konstruktor, der Parameter an die Konstruktoren der Klasse Exception weiterleitet und einen Smart-Pointer erstellt, der die neue Instanz der Klasse Exception hält.

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## Siehe auch

* Typedef [ExceptionPtr](../../exceptionptr/)
* Klasse [ExceptionWrapper](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)