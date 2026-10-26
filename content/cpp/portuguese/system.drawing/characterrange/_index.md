---
title: CharacterRange
second_title: Referência da API Aspose.Slides para C++
description: "Representa um intervalo de posições de caracteres em uma string. Esse tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos desse tipo."
type: docs
weight: 40
url: /pt/system.drawing/characterrange/
---
## CharacterRange classe

Representa um intervalo de posições de caracteres em uma string. Esse tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../../system/smartptr/) para gerenciar objetos deste tipo.

```cpp
class CharacterRange
```

## Métodos

| Método | Descrição |
| --- | --- |
|  [CharacterRange](./characterrange/)(**int32_t**, **int32_t**) | Constrói uma nova instância da classe [CharacterRange](./) que representa o intervalo especificado. |
|  [CharacterRange](./characterrange/)() | Constrói uma nova instância da classe [CharacterRange](./) que representa um intervalo vazio. |
| **int32_t** [get_First](./get_first/)() const | Retorna a posição do primeiro caractere do intervalo representado pelo objeto atual. |
| **int32_t** [get_Length](./get_length/)() const | Retorna o número de caracteres no intervalo representado pelo objeto atual. |
| **bool** [operator!=](./operator_not_equal/)(const [CharacterRange](./)\&) const | Determina se o objeto atual e o especificado representam intervalos distintos. |
| **bool** [operator==](./operator_equal_equal/)(const [CharacterRange](./)\&) const | Determina se o objeto atual e o especificado representam o mesmo intervalo. |
| void [set_First](./set_first/)(**int32_t**) | Define a posição do primeiro caractere do intervalo representado pelo objeto atual. |
| void [set_Length](./set_length/)(**int32_t**) | Retorna o número de caracteres no intervalo representado pelo objeto atual. |

## Veja Também

* Espaço de nomes [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)