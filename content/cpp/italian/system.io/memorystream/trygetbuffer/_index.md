---
title: TryGetBuffer()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce l'array di byte senza segno da cui è stato creato questo stream.
type: docs
weight: 170
url: /it/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer(ArraySegment\<uint8_t\>\&) metodo


Restituisce l'array di byte senza segno da cui è stato creato questo stream.

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\& | array di byte - parametro di output. Quando questo metodo restituisce true, il segmento di array di byte da cui è stato creato questo stream; quando questo metodo restituisce false, questo parametro è impostato al valore predefinito. |

### Valore di ritorno

True se la conversione è riuscita.

## Vedi anche

* Classe [ArraySegment](../../../system/arraysegment/)
* Classe [MemoryStream](../)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)