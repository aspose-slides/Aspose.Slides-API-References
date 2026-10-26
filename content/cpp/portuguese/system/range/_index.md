---
title: Range
second_title: Aspose.Slides para Referência da API C++
description: "Representa um intervalo com um índice de início e fim. Esse tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos desse tipo."
type: docs
weight: 1197
url: /pt/system/range/
---
## Range classe

Representa um intervalo com um índice de início e fim. Esse tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use [System::SmartPtr](../smartptr/) classe para gerenciar objetos desse tipo.

```cpp
class Range : public System::Details::BoxableObjectBase
```

## Métodos

| Método | Descrição |
| --- | --- |
| static constexpr [Range](./) [EndAt](./endat/)(const [Index](../index/)\&) | Cria um intervalo que começa no início da coleção e termina no índice final especificado. |
| **bool** [Equals](./equals/)(const [Range](./)\&) const | Determina se o intervalo atual é igual ao intervalo especificado. |
| static constexpr [Range](./) [get_All](./get_all/)() | Retorna um [Range](./) que representa a coleção inteira. |
| const [Index](../index/)\& [get_End](./get_end/)() const | Obtém o índice End. |
| const [Index](../index/)\& [get_Start](./get_start/)() const | Obtém o índice Start. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Retorna um código hash para o intervalo atual. |
| [System::ValueTuple](../valuetuple/)\<**int32_t**, **int32_t**\> [GetOffsetAndLength](./getoffsetandlength/)(**int32_t**) const | Calcula o deslocamento inicial baseado em zero e o comprimento para o comprimento da coleção especificado. |
| constexpr [Range](./range/)() | Constrói um intervalo vazio. |
| constexpr [Range](./range/)(const [Index](../index/)\&, const [Index](../index/)\&) | Constrói um [Range](./) a partir dos índices de início e fim especificados. |
| static constexpr [Range](./) [StartAt](./startat/)(const [Index](../index/)\&) | Cria um intervalo que começa no índice de início especificado e se estende até o final da coleção. |

## Veja Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)