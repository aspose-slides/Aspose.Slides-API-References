---
title: ComputeHash()
second_title: Riferimento API di Aspose.Slides per C++
description: Calcola l'hash del buffer.
type: docs
weight: 14
url: /it/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) metodo


Calcola l'hash del buffer.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Buffer di origine. |

### Valore di ritorno

Valore hash calcolato.

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) metodo


Calcola l'hash di una fetta del buffer.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Buffer di origine. |
| offset | int | Offset nel buffer di origine. |
| count | int | Numero di byte da utilizzare dal buffer di origine. |

### Valore di ritorno

Valore hash calcolato.

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) metodo


Legge lo stream fino alla fine e calcola l'hash dei dati letti.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | Stream da cui leggere i dati. |

### Valore di ritorno

Valore hash calcolato per tutti i dati del stream.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashAlgorithm](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)