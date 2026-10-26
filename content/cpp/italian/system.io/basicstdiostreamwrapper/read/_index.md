---
title: Read()
second_title: Riferimento API di Aspose.Slides per C++
description: Se la modalità di wrapping è binaria, legge il numero specificato di byte dallo stream, altrimenti legge il numero specificato di caratteri e li converte al tipo uint8_t. Scrive il risultato della lettura nell'array di byte specificato.
type: docs
weight: 66
url: /it/system.io/basicstdiostreamwrapper/read/
---
## BasicSTDIOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodo


Se la modalità di wrapping è binaria, legge il numero specificato di byte dallo stream, altrimenti legge il numero specificato di caratteri e li converte al tipo **uint8_t**. Scrive il risultato della lettura nell'array di byte specificato.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array di byte in cui scrivere i byte letti |
| offset | **int32_t** | Una posizione basata su zero in **buffer** dove iniziare a scrivere |
| count | **int32_t** | Il numero di byte da leggere |

### Valore di ritorno

Numero di byte o caratteri letti

## BasicSTDIOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metodo


Legge il numero specificato di byte dallo stream e li scrive nell'array di byte specificato.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista dell'array di byte in cui scrivere i byte letti |
| offset | **int32_t** | Una posizione basata su zero in **buffer** dove iniziare a scrivere |
| count | **int32_t** | Il numero di byte da leggere |

### Valore di ritorno

Il numero di byte letti

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [BasicSTDIOStreamWrapper](../)
* Namespace [System::IO](../../)
* Libreria [Aspose.Slides](../../../)