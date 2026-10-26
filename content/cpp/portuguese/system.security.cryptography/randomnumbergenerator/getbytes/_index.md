---
title: GetBytes()
second_title: Referência da API Aspose.Slides para C++
description: Preenche os elementos existentes do array com bytes aleatórios.
type: docs
weight: 14
url: /pt/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) método


Preenche os elementos existentes do array com bytes aleatórios.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array de bytes a ser preenchido. |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) método


Preenche a fatia existente do array com bytes aleatórios.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array de bytes a ser preenchido na fatia. |
| offset | int | Índice inicial da fatia. |
| count | int | Tamanho da fatia. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) método


Preenche os elementos existentes da visualização do array com bytes aleatórios.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Visualização do array de bytes a ser preenchida. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) método


Preenche a fatia existente da visualização do array com bytes aleatórios.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Visualização do array de bytes a ser preenchida na fatia. |
| offset | int | Índice inicial da fatia. |
| count | int | Tamanho da fatia. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) método


Preenche os elementos existentes do array de pilha com bytes aleatórios.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Array de pilha de bytes a ser preenchido. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) método


Preenche a fatia existente do array de pilha com bytes aleatórios.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Array de pilha de bytes a ser preenchido na fatia. |
| offset | int | Índice inicial da fatia. |
| count | int | Tamanho da fatia. |

## Ver Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [RandomNumberGenerator](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)