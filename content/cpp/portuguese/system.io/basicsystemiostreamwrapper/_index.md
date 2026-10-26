---
title: BasicSystemIOStreamWrapper
second_title: Aspose.Slides para C++ Referência da API
description: "Representa um invólucro semelhante a std::iostream que usou BasicSystemIOStreamBuf como buffer interno."
type: docs
weight: 53
url: /pt/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper classe

Representa um invólucro semelhante a std::iostream que usa [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) como buffer interno.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## Métodos

| Method | Description |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | Usado no construtor de movimentação e no operador de atribuição de movimentação para redefinir ponteiros e chamar [swap()](./swap/). |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Constrói uma nova instância de [BasicSystemIOStreamWrapper](./). |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | Construtor de cópia. Excluído. |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | Construtor de movimentação. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | Operador de atribuição de cópia. Excluído. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | Operador de atribuição de movimentação. |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | Chama swap *this e **right**, se eles não forem iguais. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Veja Também

* Namespace [System::IO](../)
* Biblioteca [Aspose.Slides](../../)