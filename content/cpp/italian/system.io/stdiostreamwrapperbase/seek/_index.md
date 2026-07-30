---
title: Seek()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta la posizione dello stream rappresentato dall'oggetto corrente.
type: docs
weight: 40
url: /it/system.io/stdiostreamwrapperbase/seek/
---
## STDIOStreamWrapperBase::Seek(int64_t, SeekOrigin) method

Imposta la posizione dello stream rappresentato dall'oggetto corrente.

```cpp
virtual int64_t System::IO::STDIOStreamWrapperBase<T, typename>::Seek(int64_t offset, SeekOrigin origin) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| offset | **int64_t** | L'offset in byte relativo a una posizione specificata da **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Specifica la posizione da cui e la direzione verso cui viene calcolato l'offset |

### Valore di ritorno

La nuova posizione dello stream

## Vedi anche

* Enum [SeekOrigin](../../seekorigin/)
* Classe [STDIOStreamWrapperBase](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)