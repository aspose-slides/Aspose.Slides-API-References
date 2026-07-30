---
title: Write()
second_title: Riferimento API di Aspose.Slides per C++
description: Scrive l'intervallo specificato di byte dall'array di byte specificato nello stream.
type: docs
weight: 92
url: /it/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Scrive l'intervallo specificato di byte dall'array di byte specificato nello stream.

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array contenente i byte da scrivere |
| offset | **int32_t** | Un indice basato su 0 dell'elemento in **buffer** a cui inizia l'intervallo da scrivere |
| count | **int32_t** | Il numero di elementi nell'intervallo da scrivere |

## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

Scrive l'intervallo specificato di byte dall'array di byte specificato nello stream.

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista dell'array contenente i byte da scrivere |
| offset | **int32_t** | Un indice basato su 0 dell'elemento in **buffer** a cui inizia l'intervallo da scrivere |
| count | **int32_t** | Il numero di elementi nell'intervallo da scrivere |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [MemoryStream](../)
* Spazio dei nomi [System::IO](../../)
* Library [Aspose.Slides](../../../)