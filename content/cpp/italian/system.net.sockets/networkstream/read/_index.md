---
title: Read()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge il numero specificato di byte dal flusso e li scrive nell'array di byte specificato.
type: docs
weight: 196
url: /it/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodo

Legge il numero specificato di byte dal flusso e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array di byte in cui verranno scritti i byte letti. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte da leggere. |

### Valore di ritorno

Il numero di byte letti.

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metodo

Legge il numero specificato di byte dal flusso e li scrive nell'array di byte specificato.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista dell'array di byte a cui scrivere i byte letti |
| offset | **int32_t** | Una posizione basata su 0 in **buffer** da cui iniziare a scrivere a |
| size | **int32_t** | Il numero di byte da leggere |

### Valore di ritorno

Il numero di byte letti

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [NetworkStream](../)
* Spazio dei nomi [System::Net::Sockets](../../)
* Libreria [Aspose.Slides](../../../)