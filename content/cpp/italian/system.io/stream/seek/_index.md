---
title: Seek()
second_title: Aspose.Slides per C++ Riferimento API
description: Imposta la posizione del flusso rappresentato dall'oggetto corrente.
type: docs
weight: 79
url: /it/system.io/stream/seek/
---
## Stream::Seek(int64_t, SeekOrigin) method

Imposta la posizione del flusso rappresentato dall'oggetto corrente.

```cpp
virtual int64_t System::IO::Stream::Seek(int64_t offset, SeekOrigin origin)=0
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| offset | **int64_t** | L'offset in byte relativo a una posizione specificata da **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Specifica la posizione da cui e la direzione verso la quale viene calcolato l'offset |

### Valore di ritorno

La nuova posizione del flusso

## Vedi anche

* Enum [SeekOrigin](../../seekorigin/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)