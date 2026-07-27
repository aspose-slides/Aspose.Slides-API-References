---
title: ValueTuple
second_title: Referência da API Aspose.Slides para C++
description: Classe que representa uma estrutura de dados ValueTuple.
type: docs
weight: 1444
url: /pt/system/valuetuple/
---
## classe ValueTuple

Classe que representa uma estrutura de dados [ValueTuple](./).

```cpp
template<typename ...>class ValueTuple : public System::Details::BoxableObjectBase
```

## Métodos

| Método | Descrição |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) | Determina se os objetos atuais e os especificados são idênticos. |
| **bool** [Equals](./equals/)(const [ValueTuple](./)\&) |  |
| **int32_t** [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() | Obtém a referência ao valor do componente do objeto [ValueTuple](./). |
| const std::tuple_element_t\<[Index](../index/), tuple_t\>\& [Item](./item/)() const | Obtém o valor do componente do objeto [ValueTuple](./). |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [ValueTuple](./)\<OtherArgs...\>\&) |  |
| [ValueTuple](./)\& [operator=](./operator_equal/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Desconstrói o objeto para esta tupla de valores. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTuple](./)\&) const |  |
| [System::String](../string/) [ToString](./tostring/)() const |  |
| tuple_t\& [tuple](./tuple/)() |  |
| const tuple_t\& [tuple](./tuple/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Retorna uma referência ao objeto [TypeInfo](../typeinfo/) que representa as informações de tipo da classe [ValueTuple](./). |
|  [ValueTuple](./valuetuple/)() |  |
|  [ValueTuple](./valuetuple/)(Args...) | Constrói um objeto tupla. |

## Ver também

* Namespace [System](../)
* Library [Aspose.Slides](../../)