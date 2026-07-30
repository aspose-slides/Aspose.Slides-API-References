---
title: GetBytes()
second_title: Riferimento API di Aspose.Slides per C++
description: Riempie gli elementi dell'array esistente con byte casuali.
type: docs
weight: 14
url: /it/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) metodo


Riempie gli elementi dell'array esistente con byte casuali.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array di byte da riempire. |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) metodo


Riempie una porzione dell'array esistente con byte casuali.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Array di byte da riempire la porzione. |
| offset | int | Indice di inizio della porzione. |
| count | int | Dimensione della porzione. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) metodo


Riempie gli elementi della vista dell'array esistente con byte casuali.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Vista dell'array di byte da riempire. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) metodo


Riempie una porzione della vista dell'array esistente con byte casuali.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Vista dell'array di byte da riempire la porzione. |
| offset | int | Indice di inizio della porzione. |
| count | int | Dimensione della porzione. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) metodo


Riempie gli elementi dello stack array esistente con byte casuali.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Stack array di byte da riempire. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) metodo


Riempie una porzione dello stack array esistente con byte casuali.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Stack array di byte da riempire la porzione. |
| offset | int | Indice di inizio della porzione. |
| count | int | Dimensione della porzione. |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [RandomNumberGenerator](../)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Libreria [Aspose.Slides](../../../)