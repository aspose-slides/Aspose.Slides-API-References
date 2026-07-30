---
title: Write()
second_title: Riferimento API Aspose.Slides per C++
description: Scrive l'intervallo specificato di byte dall'array di byte specificato al flusso.
type: docs
weight: 209
url: /it/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Scrive l'intervallo specificato di byte dall'array di byte specificato al flusso.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array che contiene i byte da scrivere. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di elementi nell'intervallo da scrivere. |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

Scrive l'intervallo specificato di byte dall'array di byte specificato al flusso.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista dell'array che contiene i byte da scrivere |
| offset | **int32_t** | Un indice basato su 0 dell'elemento in **buffer** in cui inizia l'intervallo da scrivere |
| size | **int32_t** | Il numero di elementi nell'intervallo da scrivere |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)