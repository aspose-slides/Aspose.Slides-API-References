---
title: EnumValues
second_title: Referência da API Aspose.Slides para C++
description: Fornece informações de meta sobre constantes de enumeração do tipo enum E.
type: docs
weight: 794
url: /pt/system/enumvalues/
---
## EnumValues classe

Fornece informações de meta sobre constantes de enumeração do tipo enum **E**.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| E | O tipo de enumeração |
## Métodos

| Método | Descrição |
| --- | --- |
|  [EnumValues](./enumvalues/)() | Constrói uma instância. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | Retorna um array contendo todos os nomes da enumeração **E**. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | Recupera um array com os nomes das constantes em uma enumeração especificada. |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | Retorna o tipo subjacente da enumeração especificada. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Retorna o tipo subjacente da enumeração especificada. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | Retorna o valor encapsulado da constante enum com o nome especificado. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | Retorna o valor encapsulado da constante enum com o valor especificado. |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | Retorna um array contendo todos os valores da enumeração **E**. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | Retorna um array contendo todos os valores do tipo de enumeração especificado. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Retorna um objeto que representa um valor de constante enum do tipo de enumeração especificado com o nome especificado. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Converte o valor inteiro sem sinal de 64 bits especificado para um membro da enumeração. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Converte o objeto especificado com um valor inteiro para um membro da enumeração. |
| virtual  [~EnumValues](./~enumvalues/)() | Destrutor. |

## Veja Também

* Classe [EnumValuesBase](../enumvaluesbase/)
* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)