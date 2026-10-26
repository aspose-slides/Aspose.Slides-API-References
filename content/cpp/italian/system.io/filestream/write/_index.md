---
title: Write()
second_title: Riferimento API di Aspose.Slides per C++
description: Scrive l'intervallo specificato di byte dall'array di byte specificato al flusso.
type: docs
weight: 248
url: /it/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodo

Scrive l'intervallo specificato di byte dall'array di byte specificato al flusso.

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array contenente i byte da scrivere. |
| offset | **int32_t** | Un indice basato su 0 dell'elemento in **buffer** in cui inizia il sottointervallo da scrivere. |
| count | **int32_t** | Il numero di elementi nel sottointervallo da scrivere. |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metodo

Scrive l'intervallo specificato di byte dall'array di byte specificato al flusso.

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista dell'array contenente i byte da scrivere. |
| offset | **int32_t** | Un indice basato su 0 dell'elemento in **buffer** in cui inizia il sottointervallo da scrivere. |
| count | **int32_t** | Il numero di elementi nel sottointervallo da scrivere. |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [FileStream](../)
* Namespace [System::IO](../../)
* Libreria [Aspose.Slides](../../../)