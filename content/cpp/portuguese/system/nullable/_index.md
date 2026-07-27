---
title: Nullable
second_title: Referência da API Aspose.Slides para C++
description: Declaração antecipada.
type: docs
weight: 1106
url: /pt/system/nullable/
---
## Classe Nullable

Declaração antecipada.

```cpp
template<typename T>class Nullable
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo de valor subjacente que é estendido pela classe [Nullable](./) |

## Métodos

| Método | Descrição |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | Determina se o valor representado pelo objeto atual é igual ao valor representado pelo objeto [Nullable](./) especificado. |
| **bool** [get_HasValue](./get_hasvalue/)() const | Determina se o objeto atual representa algum valor. |
| T [get_Value](./get_value/)() const | Retorna uma cópia do valor representado pelo objeto atual. |
| int [GetHashCode](./gethashcode/)() const | Retorna um código hash para o objeto atual. |
| T [GetValueOrDefault](./getvalueordefault/)(T) | Retorna o valor representado pelo objeto atual ou o valor especificado se o valor representado pelo objeto atual for nulo. |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | Determina se o objeto atual representa um valor nulo. |
| [Nullable](./nullable/)() | Constrói uma instância que representa um valor nulo. |
| [Nullable](./nullable/)(std::nullptr_t) | Constrói uma instância que representa nulo. |
| [Nullable](./nullable/)(const T1\&) | Constrói uma instância da classe [Nullable](./) que representa o valor especificado convertido (se necessário) para o tipo subjacente T. |
| [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | Constrói uma instância que representa um valor que é representado pelo objeto [Nullable](./) especificado. O objeto nullable especificado pode representar um valor de tipo diferente do tipo subjacente da instância construída, caso em que o valor representado é convertido para um valor do tipo T. |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | Função auxiliar para verificar se este e **other** não são nulos e chamar uma lambda se for o caso. Usada nas implementações. |
| [operator const T &](./operator_const_t__and/)() const | Retorna uma referência constante ao valor representado pelo objeto atual. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Determina se o valor representado pelo objeto atual não é nulo. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | Determina se o valor representado pelo objeto atual não é igual ao valor especificado. |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | Determina se o valor representado pelo objeto atual não é igual ao valor representado pelo objeto [Nullable](./) especificado. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | Aplica [operator&=()](./operator_and_equal/) ao valor representado pelo objeto atual usando o valor especificado como argumento do lado direito. |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | Retorna uma instância construída por padrão da classe Nullable<T>. |
| auto [operator+](./operator_plus/)(const T1\&) const | Soma valores nullable e não nullable. |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | Soma valores nullable. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | Redefine o objeto atual para representar um valor nulo. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | Aplica [operator+=()](./operator_plus_equal/) ao valor representado pelo objeto atual usando o valor especificado como argumento do lado direito. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | Aplica [operator+=()](./operator_plus_equal/) ao valor representado pelo objeto atual usando o valor representado pelo objeto [Nullable](./) especificado como argumento do lado direito. |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | Subtrai valores nullable e valores nulos apontados. |
| auto [operator-](./operator_minus/)(const T1\&) const | Subtrai valores nullable e não nullable. |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | Subtrai valores nullable. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | Retorna uma instância da classe [Nullable](./) que representa um valor nulo. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | Aplica [operator-=()](./operator_minus_equal/) ao valor representado pelo objeto atual usando o valor especificado como argumento do lado direito. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | Aplica [operator-=()](./operator_minus_equal/) ao valor representado pelo objeto atual usando o valor representado pelo objeto [Nullable](./) especificado como argumento do lado direito. |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | Sempre retorna false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | Determina se o valor representado pelo objeto atual é menor que o valor especificado ao aplicar [operator<()](./operator_less/) a esses valores. |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | Determina se o valor representado pelo objeto atual é menor que o valor representado pelo objeto [Nullable](./) especificado ao aplicar [operator<()](./operator_less/) a esses valores. |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | Sempre retorna false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | Determina se o valor representado pelo objeto atual é menor ou igual ao valor especificado ao aplicar [operator<=()](./operator_less_equal/) a esses valores. |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | Determina se o valor representado pelo objeto atual é menor ou igual ao valor representado pelo objeto [Nullable](./) especificado ao aplicar [operator<=()](./operator_less_equal/) a esses valores. |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | Atribui um nulo ao objeto atual. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | Substitui o valor atualmente representado do objeto pelo especificado. |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | Substitui o valor atualmente representado do objeto pelo especificado. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Determina se o valor representado pelo objeto atual é nulo. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | Determina se o valor representado pelo objeto atual é igual ao valor especificado. |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | Determina se o valor representado pelo objeto atual é igual ao valor representado pelo objeto [Nullable](./) especificado. |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | Sempre retorna false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | Determina se o valor representado pelo objeto atual é maior que o valor especificado ao aplicar [operator>()](./operator_greater/) a esses valores. |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | Determina se o valor representado pelo objeto atual é maior que o valor representado pelo objeto [Nullable](./) especificado ao aplicar [operator>()](./operator_greater/) a esses valores. |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | Sempre retorna false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | Determina se o valor representado pelo objeto atual é maior ou igual ao valor representado pelo objeto especificado ao aplicar [operator>=()](./operator_greater_equal/) a esses valores. |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | Determina se o valor representado pelo objeto atual é maior ou igual ao valor representado pelo objeto [Nullable](./) especificado ao aplicar [operator>=()](./operator_greater_equal/) a esses valores. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | Aplica [operator|=()](./operator_or_equal/) ao valor representado pelo objeto atual usando o valor especificado como argumento do lado direito. |
| void [reset](./reset/)() | Define o valor atualmente representado como nulo. |
| void [set_Value](./set_value/)(const T\&) | Define um novo valor ao objeto nullable. |
| [String](../string/) [ToString](./tostring/)() const | Converte o valor representado pelo objeto atual para string. |

## Tipos Definidos

| Typedef | Descrição |
| --- | --- |
| [ValueType](./valuetype/) | Um alias para um tipo do valor representado por esta classe. |

## Observações

Representa um valor do tipo especificado que pode ser atribuído nulo. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../smartptr/) para gerenciar objetos deste tipo.

## Ver Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)