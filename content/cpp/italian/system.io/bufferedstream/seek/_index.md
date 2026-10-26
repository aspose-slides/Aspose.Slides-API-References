---
title: Seek()
second_title: Riferimento API Aspose.Slides per C++
description: Imposta la posizione dello stream rappresentato dall'oggetto corrente.
type: docs
weight: 79
url: /it/system.io/bufferedstream/seek/
---
## BufferedStream::Seek(int64_t, SeekOrigin) metodo

Imposta la posizione dello stream rappresentato dall'oggetto corrente.

```cpp
virtual int64_t System::IO::BufferedStream::Seek(int64_t offset, SeekOrigin origin) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| offset | **int64_t** | L'offset in byte relativo a una posizione specificata da **origin** |
| origin | [SeekOrigin](../../seekorigin/) | Specifica la posizione da cui e la direzione verso cui viene calcolato l'offset |

### Valore restituito

La nuova posizione dello stream

## Vedi anche

* Enum [SeekOrigin](../../seekorigin/)
* Classe [BufferedStream](../)
* Spazio dei nomi [System::IO](../../)
* Library [Aspose.Slides](../../../)