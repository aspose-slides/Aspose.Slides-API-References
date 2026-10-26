---
title: Read()
second_title: Riferimento API Aspose.Slides per C++
description: Legge il numero specificato di byte dallo stream e li scrive nell'array di byte specificato.
type: docs
weight: 79
url: /it/system.io/memorystream/read/
---
## MemoryStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodo


Legge il numero specificato di byte dallo stream e li scrive nell'array di byte specificato.

```cpp
int32_t System::IO::MemoryStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Parametri

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array di byte in cui scrivere i byte letti |
| offset | **int32_t** | Una posizione indicizzata da 0 in **buffer** dove iniziare a scrivere |
| count | **int32_t** | Il numero di byte da leggere |

### Valore di ritorno

Il numero di byte letti

## MemoryStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metodo


Legge il numero specificato di byte dallo stream e li scrive nell'array di byte specificato.

```cpp
int32_t System::IO::MemoryStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Parametri

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista dell'array di byte in cui scrivere i byte letti |
| offset | **int32_t** | Una posizione indicizzata da 0 in **buffer** dove iniziare a scrivere |
| count | **int32_t** | Il numero di byte da leggere |

### Valore di ritorno

Il numero di byte letti

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)