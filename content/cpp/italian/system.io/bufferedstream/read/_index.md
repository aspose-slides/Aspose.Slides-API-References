---
title: Read()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge il numero specificato di byte dallo stream sottostante e li scrive nell'array di byte specificato.
type: docs
weight: 53
url: /it/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodo

Legge il numero specificato di byte dallo stream sottostante e li scrive nell'array di byte specificato.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array di byte in cui scrivere i byte letti |
| offset | **int32_t** | Una posizione basata su zero in **buffer** da cui iniziare la scrittura |
| count | **int32_t** | Il numero di byte da leggere |

### Valore di ritorno

Il numero di byte letti

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metodo

Legge il numero specificato di byte dallo stream sottostante e li scrive nell'array di byte specificato.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | L'array di byte in cui scrivere i byte letti |
| offset | **int32_t** | Una posizione basata su zero in **buffer** da cui iniziare la scrittura |
| count | **int32_t** | Il numero di byte da leggere |

### Valore di ritorno

Il numero di byte letti

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [BufferedStream](../)
* Namespace [System::IO](../../)
* Libreria [Aspose.Slides](../../../)