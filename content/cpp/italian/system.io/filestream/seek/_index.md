---
title: Seek()
second_title: Riferimento API di Aspose.Slides for C++
description: Imposta la posizione del flusso rappresentato dall'oggetto corrente.
type: docs
weight: 209
url: /it/system.io/filestream/seek/
---
## FileStream::Seek(int64_t, SeekOrigin) metodo

Imposta la posizione del flusso rappresentato dall'oggetto corrente.

```cpp
int64_t System::IO::FileStream::Seek(int64_t offset, SeekOrigin origin) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| offset | **int64_t** | L'offset in byte relativo a una posizione specificata da **origin**. |
| origin | [SeekOrigin](../../seekorigin/) | Specifica la posizione da cui e la direzione verso cui viene calcolato l'offset. |

### Valore di ritorno

La nuova posizione del flusso.

## Vedi anche

* Enum [SeekOrigin](../../seekorigin/)
* Classe [FileStream](../)
* Namespace [System::IO](../../)
* Libreria [Aspose.Slides](../../../)