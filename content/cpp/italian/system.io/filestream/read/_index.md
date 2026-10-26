---
title: Read()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge il numero specificato di byte dallo stream e li scrive nell'array di byte specificato.
type: docs
weight: 183
url: /it/system.io/filestream/read/
---
## FileStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodo


Legge il numero specificato di byte dallo stream e li scrive nell'array di byte specificato.

```cpp
int32_t System::IO::FileStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array di byte in cui scrivere i byte letti. |
| offset | **int32_t** | Una posizione basata su 0 in **buffer** in cui iniziare la scrittura. |
| count | **int32_t** | Il numero di byte da leggere. |

### Valore di ritorno

Il numero di byte letti.

## FileStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metodo


Legge il numero specificato di byte dallo stream e li scrive nell'array di byte specificato.

```cpp
int32_t System::IO::FileStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista dell'array di byte in cui scrivere i byte letti. |
| offset | **int32_t** | Una posizione basata su 0 in **buffer** in cui iniziare la scrittura. |
| count | **int32_t** | Il numero di byte da leggere. |

### Valore di ritorno

Il numero di byte letti.

## Vedi anche

* Definizione di tipo [ArrayPtr](../../../system/arrayptr/)
* Classe [FileStream](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)