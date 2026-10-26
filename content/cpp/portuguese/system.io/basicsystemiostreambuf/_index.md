---
title: BasicSystemIOStreamBuf
second_title: Referência da API Aspose.Slides para C++
description: "Representa um buffer que envolve fluxos semelhantes a System::IO::Stream e permite que sejam usados como um buffer interno de fluxos semelhantes a std::iostream."
type: docs
weight: 40
url: /pt/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf classe

Representa um buffer que envolve fluxos semelhantes a [System::IO::Stream](../stream/) e permite que sejam usados como um buffer interno de fluxos semelhantes a std::iostream.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## Métodos

| Método | Descrição |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | Usado no construtor de movimento e no operador de atribuição de movimento para redefinir ponteiros e chamar [swap()](./swap/). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | Constrói uma nova instância de [BasicSystemIOStreamBuf](./). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | Constrói uma nova instância de [BasicSystemIOStreamBuf](./). |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | Construtor de cópia. Excluído. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | Construtor de movimento. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | Operador de atribuição de cópia. Excluído. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | Operador de atribuição de movimento. |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | Chama swap *this e right, se não forem iguais. |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | Destrutor. |

## Definições de Tipo

| Typedef | Descrição |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## Veja Também

* Espaço de nomes [System::IO](../)
* Biblioteca [Aspose.Slides](../../)