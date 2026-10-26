---
title: PrintTo()
second_title: Referência da API Aspose.Slides para C++
description: Imprime o valor no ostream. Principalmente usado para depuração.
type: docs
weight: 2146
url: /pt/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) função

Imprime o valor no ostream. Principalmente usado para depuração.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) função

Imprime o valor no ostream. Principalmente usado para depuração.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) função

Grava o valor representado pelo objeto especificado no fluxo de saída especificado.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | O objeto [Decimal](../decimal/) a ser impresso no fluxo |
| os | ::std::ostream * | O fluxo para o qual o objeto especificado será impresso |

## System::PrintTo(const Details_Exception\&, std::ostream *) função

Imprime o valor no ostream. Principalmente usado para depuração.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) função

Imprime o valor no ostream. Principalmente usado para depuração.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) função

Imprime o valor no ostream. Principalmente usado para depuração.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) função

Imprime o valor no ostream. Principalmente usado para depuração.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) função

Imprime o valor no ostream. Principalmente usado para depuração.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) função

Imprime o valor no ostream. Principalmente usado para depuração.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) função

Imprime o valor no ostream. Principalmente usado para depuração.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) função

Imprime a string no ostream. Principalmente usado para depuração.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [System::String](../string/)\& | para imprimir. |
| os | std::ostream * | ostream de destino. |

## System::PrintTo(TimeSpan, std::ostream *) função

Imprime o valor no ostream. Principalmente usado para depuração.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) função

Imprime o valor no ostream. Principalmente usado para depuração.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## Veja Também

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
* Espaço de nomes [System](../)
* Library [Aspose.Slides](../../)