---
title: ExceptionWrapper
second_title: Aspose.Slides para C++ Referência da API
description: Modelo que representa um wrapper de exceções que são derivadas da classe Exception.
type: docs
weight: 833
url: /pt/system/exceptionwrapper/
---
## ExceptionWrapper classe


Modelo que representa um wrapper de exceções que são derivadas da classe Exception.

```cpp
template<typename T>class ExceptionWrapper
```

## Métodos

| Method | Description |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | Constrói uma instância nula da classe [ExceptionWrapper](./) que não representa nenhuma exceção. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | Constrói uma instância da classe [ExceptionWrapper](./) que contém o ponteiro passado. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | Construtor de cópia. |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | Construtor de movimento. |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | Construtor que encaminha parâmetros para os construtores da classe Exception e cria um smart pointer que mantém uma nova instância da classe Exception. |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | Operador de cast implícito para SharedPtr<Object> |
| T * [operator->](./operator_minus_greater/)() const | Permite acessar membros do objeto Exception. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | Operador de atribuição. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | Operador de atribuição de movimento. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Atalho para obter o objeto [System::TypeInfo](../typeinfo/) para o tipo Exception. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ExceptionType](./exceptiontype/) | Usado para funções de casting. |
## Veja Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)