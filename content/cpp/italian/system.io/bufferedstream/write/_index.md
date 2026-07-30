---
title: Write()
second_title: Aspose.Slides per C++ Riferimento API
description: Scrive il sottointervallo specificato di byte dall'array di byte specificato nello stream sottostante.
type: docs
weight: 66
url: /it/system.io/bufferedstream/write/
---
## BufferedStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodo

Scrive il sottointervallo specificato di byte dall'array di byte specificato nello stream sottostante.

```cpp
virtual void System::IO::BufferedStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | L'array contenente i byte da scrivere |
| offset | **int32_t** | Un indice basato su 0 dell'ellemnet in **buffer** al quale inizia il sottointervallo da scrivere |
| count | **int32_t** | Il numero di elementi nel sottointervallo da scrivere |

## BufferedStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metodo

Scrive il sottointervallo specificato di byte dall'array di byte specificato nello stream sottostante.

```cpp
virtual void System::IO::BufferedStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | L'array contenente i byte da scrivere |
| offset | **int32_t** | Un indice basato su 0 dell'ellemnet in **buffer** al quale inizia il sottointervallo da scrivere |
| count | **int32_t** | Il numero di elementi nel sottointervallo da scrivere |

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [BufferedStream](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)