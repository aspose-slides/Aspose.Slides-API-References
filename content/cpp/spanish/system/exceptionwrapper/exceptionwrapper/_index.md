---
title: ExceptionWrapper()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una instancia nula de la clase ExceptionWrapper que no representa ninguna excepción.
type: docs
weight: 14
url: /es/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) constructor

Construye una instancia nula de la clase [ExceptionWrapper](../) que no representa ninguna excepción.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) constructor

Construye una instancia de la clase [ExceptionWrapper](../) que contiene el puntero pasado.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | Puntero inteligente a la instancia de la clase Exception. |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) constructor

Constructor de copia.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | Otra instancia de la clase wrapper que debe copiarse. |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) constructor

Constructor de movimiento.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | Otra instancia de la clase wrapper que debe moverse. |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) constructor

Constructor que reenvía los parámetros a los constructores de la clase Exception y crea un puntero inteligente que contiene una nueva instancia de la clase Exception.

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## See Also

* Typedef [ExceptionPtr](../../exceptionptr/)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)