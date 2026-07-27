---
title: BasicSystemIStreamWrapper
second_title: Referência da API Aspose.Slides para C++
description: "Representa um wrapper semelhante a std::istream que usa BasicSystemIOStreamBuf como buffer interno."
type: docs
weight: 66
url: /pt/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper classe


Representa um wrapper semelhante a std::istream que usa [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) como buffer interno.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## Métodos

| Método | Descrição |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | Usado no construtor de movimentação e no operador de atribuição por movimentação para redefinir ponteiros e chamar [swap()](./swap/). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Constrói uma nova instância do [BasicSystemIStreamWrapper](./). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | Construtor de cópia. Excluído. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | Construtor de movimento. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | Operador de atribuição de cópia. Excluído. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | Operador de atribuição de movimento. |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | Chamada para trocar *this e **right**, se não forem iguais. |
## Tipos definidos

| Typedef | Descrição |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
## Veja Também

* Espaço de nomes [System::IO](../)
* Biblioteca [Aspose.Slides](../../)