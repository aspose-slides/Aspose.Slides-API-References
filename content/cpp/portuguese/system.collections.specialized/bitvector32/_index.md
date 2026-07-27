---
title: BitVector32
second_title: Referência da API Aspose.Slides para C++
description: Fornece um vetor de bits simples e leve com acesso fácil a inteiros ou booleanos a um armazenamento de 32 bits.
type: docs
weight: 1
url: /pt/system.collections.specialized/bitvector32/
---
## BitVector32 classe

Fornece um vetor de bits simples e leve com acesso fácil a inteiro ou [Boolean](../../system/boolean/) a um armazenamento de 32 bits.

```cpp
class BitVector32
```

## Métodos

| Método | Descrição |
| --- | --- |
|  [BitVector32](./bitvector32/)() | Inicializa uma nova instância vazia do [BitVector32](./). |
|  [BitVector32](./bitvector32/)(**int32_t**) | Inicializa uma nova instância da estrutura [BitVector32](./) com os dados internos especificados. |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | Inicializa uma nova instância da estrutura [BitVector32](./) com as informações no valor especificado. |
| static **int32_t** [CreateMask](./createmask/)() | Cria a primeira máscara de uma série. |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | Cria a próxima máscara de uma série. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | Cria a primeira seção de uma série, com o valor máximo especificado. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | Cria a próxima seção de uma série, com o valor máximo especificado. |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | Determina se o objeto especificado é o mesmo que o atual. |
| **int32_t** [get_Data](./get_data/)() | retorna os dados brutos armazenados neste vetor de bits... |
| **int32_t** [GetHashCode](./gethashcode/)() const | Retorna um código hash para o objeto atual. |
| **bool** [idx_get](./idx_get/)(**int32_t**) | Obtém um valor que indica se todos os bits especificados estão definidos. |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | Obtém o valor da seção especificada. |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | Define um valor que indica se todos os bits especificados estão definidos. |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | Define o valor para a seção especificada. |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | Converte o valor representado pelo parâmetro value para string. |
| [String](../../system/string/) [ToString](./tostring/)() const | Converte o valor representado pelo objeto atual para string. |

## Veja Também

* Namespace [System::Collections::Specialized](../)
* Biblioteca [Aspose.Slides](../../)