---
title: Index
second_title: Referência da API Aspose.Slides para C++
description: "Representa um índice em uma coleção. O índice pode ser a partir do início ou do final. Esse tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos desse tipo."
type: docs
weight: 1015
url: /pt/system/index/
---
## classe Index

Representa um índice em uma coleção. O índice pode ser a partir do início ou do final. Esse tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../smartptr/) para gerenciar objetos desse tipo.

```cpp
class Index : public System::Details::BoxableObjectBase
```

## Métodos

| Método | Descrição |
| --- | --- |
| **bool** [Equals](./equals/)(const [Index](./)\&) const | Determina se a instância atual e o [Index](./) especificado representam a mesma posição. |
| static constexpr [Index](./) [FromEnd](./fromend/)(**int32_t**) | Cria um [Index](./) que é relativo ao final da coleção. |
| static constexpr [Index](./) [get_End](./get_end/)() | Obtém um objeto [Index](./) que representa o final de uma coleção. |
| constexpr **bool** [get_IsFromEnd](./get_isfromend/)() const | Obtém um valor que indica se o índice é a partir do final. |
| static constexpr [Index](./) [get_Start](./get_start/)() | Obtém um objeto [Index](./) que representa o início de uma coleção. |
| constexpr **int32_t** [get_Value](./get_value/)() const | Obtém o valor do índice. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Retorna um código hash para o índice atual. |
| **int32_t** [GetOffset](./getoffset/)(**int32_t**) const | Converte o [Index](./) atual em um deslocamento a partir do início de uma coleção com o comprimento especificado. |
| constexpr [Index](./index/)() | Constrói uma instância que representa o início de uma coleção. |
| constexpr [Index](./index/)(**int32_t**) | Constrói uma instância que representa a posição especificada a partir do início de uma coleção. |
| constexpr [Index](./index/)(**int32_t**, **bool**) | Constrói uma instância que representa o índice especificado. |

## Veja Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)