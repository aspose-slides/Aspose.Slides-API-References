---
title: Read()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge il numero specificato di byte dal flusso e li scrive nell'array di byte specificato.
type: docs
weight: 144
url: /it/system.io/unmanagedmemorystream/read/
---
## UnmanagedMemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodo


Legge il numero specificato di byte dal flusso e li scrive nell'array di byte specificato.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array di byte in cui scrivere i byte letti |
| offset | **int32_t** | Una posizione basata su 0 in **buffer** da cui iniziare a scrivere |
| count | **int32_t** | Il numero di byte da leggere |

### Valore di ritorno

Il numero di byte letti

## UnmanagedMemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metodo


Legge il numero specificato di byte dal flusso e li scrive nell'array di byte specificato.

```cpp
virtual int32_t System::IO::UnmanagedMemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista dell'array di byte in cui scrivere i byte letti |
| offset | **int32_t** | Una posizione basata su 0 in **buffer** da cui iniziare a scrivere |
| count | **int32_t** | Il numero di byte da leggere |

### Valore di ritorno

Il numero di byte letti

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [UnmanagedMemoryStream](../)
* Spazio dei nomi [System::IO](../../)
* Library [Aspose.Slides](../../../)