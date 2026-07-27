---
title: BasicSystemOStreamWrapper
second_title: Aspose.Slides para C++ Referência da API
description: "Representa um wrapper semelhante a std::ostream que usa BasicSystemIOStreamBuf como buffer interno."
type: docs
weight: 79
url: /pt/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper classe


Representa um wrapper similar a std::ostream que usa [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) como buffer interno.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## Métodos

| Method | Description |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | Usado no construtor de movimentação e no operador de atribuição de movimentação para redefinir ponteiros e chamar [swap()](./swap/). |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Constrói uma nova instância de [BasicSystemOStreamWrapper](./). |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | Construtor de cópia. Excluído. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | Construtor de movimentação. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | Operador de atribuição de cópia. Excluído. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | Operador de atribuição de movimentação. |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | Chama swap entre *this e **right**, se não forem iguais. |

## Tipos Definidos

| Typedef | Description |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Veja Também

* Namespace [System::IO](../)
* Biblioteca [Aspose.Slides](../../)