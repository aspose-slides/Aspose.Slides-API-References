---
title: ExceptionWrapper()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma instância nula da classe ExceptionWrapper que não representa nenhuma exceção.
type: docs
weight: 14
url: /pt/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) construtor


Constrói uma instância nula da classe [ExceptionWrapper](../) que não representa nenhuma exceção.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) construtor


Constrói uma instância da classe [ExceptionWrapper](../) que contém o ponteiro passado.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | Ponteiro inteligente para a instância da classe Exception. |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) construtor


Construtor de cópia.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | Outra instância da classe wrapper que deve ser copiada. |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) construtor


Construtor de movimentação.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | Outra instância da classe wrapper que deve ser movida. |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) construtor


Construtor que encaminha os parâmetros para os construtores da classe Exception e cria um ponteiro inteligente que contém a nova instância da classe Exception.

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## Veja Também

* Typedef [ExceptionPtr](../../exceptionptr/)
* Classe [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)