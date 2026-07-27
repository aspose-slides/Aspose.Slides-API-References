---
title: PrintTo()
second_title: Referencia de API de Aspose.Slides para C++
description: Imprime el valor en ostream. Principalmente usado para depuración.
type: docs
weight: 2146
url: /es/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) función


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) función


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) función


Escribe el valor representado por el objeto especificado en el flujo de salida especificado.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | El objeto [Decimal](../decimal/) para imprimir en el flujo |
| os | ::std::ostream * | El flujo en el que imprimir el objeto especificado |

## System::PrintTo(const Details_Exception\&, std::ostream *) función


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) función


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) función


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) función


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) función


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) función


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) función


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) función


Imprime la cadena en ostream. Principalmente usado para depuración.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [System::String](../string/)\& | para imprimir. |
| os | std::ostream * | flujo de salida objetivo. |

## System::PrintTo(TimeSpan, std::ostream *) función


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) función


Imprime el valor en ostream. Principalmente usado para depuración.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## Ver también

* Clase [DateTime](../datetime/)
* Clase [DateTimeOffset](../datetimeoffset/)
* Clase [Decimal](../decimal/)
* Clase [Details_Exception](../details_exception/)
* Clase [ExceptionWrapper](../exceptionwrapper/)
* Clase [Guid](../guid/)
* Clase [Nullable](../nullable/)
* Clase [Object](../object/)
* Clase [SmartPtr](../smartptr/)
* Clase [String](../string/)
* Clase [TimeSpan](../timespan/)
* Clase [WeakPtr](../weakptr/)
* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)