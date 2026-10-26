---
title: EnumValuesBase
second_title: Aspose.Slides para C++ Referência da API
description: Uma classe base para uma classe que representa informações de metadados de um tipo enumeração.
type: docs
weight: 807
url: /pt/system/enumvaluesbase/
---
## classe EnumValuesBase

Uma classe base para uma classe que representa informações de metadados de um tipo enumeração.

```cpp
class EnumValuesBase
```

## Métodos

| Método | Descrição |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | Recupera uma matriz com os nomes das constantes em uma enumeração especificada. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Retorna o tipo subjacente da enumeração especificada. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | Retorna uma matriz contendo todos os valores do tipo de enumeração especificado. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Retorna um objeto que representa o valor de uma constante de enumeração do tipo de enumeração especificado com o nome especificado. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Converte o valor inteiro sem sinal de 64 bits especificado em um membro da enumeração. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Converte o objeto especificado com um valor inteiro em um membro da enumeração. |

## Veja Também

* Espaço de nomes [System](../)
* Library [Aspose.Slides](../../)