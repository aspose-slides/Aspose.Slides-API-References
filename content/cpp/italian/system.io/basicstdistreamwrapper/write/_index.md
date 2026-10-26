---
title: Write()
second_title: Riferimento API di Aspose.Slides per C++
description: Se la modalità di wrapping è binaria, scrive nello stream la sottointervallo specificata di byte dall'array di byte specificato; altrimenti converte la sottointervallo specificata di byte dall'array di byte specificato al tipo char_type e poi scrive il risultato nello stream. Non supportato!
type: docs
weight: 79
url: /it/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodo

Se la modalità di wrapping è binaria, scrive nello stream la sottointervallo specificata di byte dall'array di byte specificato; altrimenti converte la sottointervallo specificata di byte dall'array di byte specificato al tipo char_type e quindi scrive il risultato nello stream. Non supportato!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array contenente i byte da scrivere. |
| offset | **int32_t** | Un indice basato su 0 dell'elemento in **buffer** in cui inizia la sottointervallo da scrivere. |
| count | **int32_t** | Il numero di elementi nella sottointervallo da scrivere. |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metodo

Scrive la sottointervallo specificata di byte dall'array di byte specificato nello stream.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | La vista dell'array contenente i byte da scrivere |
| offset | **int32_t** | Un indice basato su 0 dell'elemento in **buffer** in cui inizia la sottointervallo da scrivere |
| count | **int32_t** | Il numero di elementi nella sottointervallo da scrivere |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [BasicSTDIStreamWrapper](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)