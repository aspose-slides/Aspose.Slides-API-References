---
title: Read()
second_title: Riferimento API Aspose.Slides per C++
description: Se la modalità di wrapping è binaria, legge il numero specificato di byte dal flusso; altrimenti legge il numero specificato di caratteri e li converte al tipo uint8_t. Scrive il risultato della lettura nell'array di byte specificato.
type: docs
weight: 66
url: /it/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Se la modalità di wrapping è binaria, legge il numero specificato di byte dal flusso; altrimenti legge il numero specificato di caratteri e li converte al tipo **uint8_t**. Scrive il risultato della lettura nell'array di byte specificato.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array di byte su cui scrivere i byte letti |
| offset | **int32_t** | Una posizione a base 0 in **buffer** per iniziare a scrivere |
| count | **int32_t** | Il numero di byte da leggere |

### Valore restituito

Numero di byte o caratteri letti

## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

Legge il numero specificato di byte dal flusso e li scrive nell'array di byte specificato.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista dell'array di byte su cui scrivere i byte letti |
| offset | **int32_t** | Una posizione a base 0 in **buffer** per iniziare a scrivere |
| count | **int32_t** | Il numero di byte da leggere |

### Valore restituito

Il numero di byte letti

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)