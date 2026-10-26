---
title: Write()
second_title: Riferimento API di Aspose.Slides per C++
description: Se la modalità di wrapping è binaria, scrive sullo stream il sottointervallo specificato di byte dall'array di byte specificato; altrimenti converte il sottointervallo specificato di byte dall'array di byte specificato al tipo char_type e poi scrive il risultato sullo stream.
type: docs
weight: 79
url: /it/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodo

Se la modalità di wrapping è binaria, scrive sullo stream il sottointervallo specificato di byte dall'array di byte specificato; altrimenti converte il sottointervallo specificato di byte dall'array di byte specificato al tipo char_type e poi scrive il risultato sullo stream.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array contenente i byte da scrivere |
| offset | **int32_t** | Un indice base-0 dell'elemento in **buffer** al quale inizia il sottointervallo da scrivere |
| count | **int32_t** | Il numero di elementi nel sottointervallo da scrivere |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metodo

Scrive il sottointervallo specificato di byte dall'array di byte specificato sullo stream.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista dell'array contenente i byte da scrivere |
| offset | **int32_t** | Un indice base-0 dell'elemento in **buffer** al quale inizia il sottointervallo da scrivere |
| count | **int32_t** | Il numero di elementi nel sottointervallo da scrivere |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [BasicSTDIOStreamWrapper](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)