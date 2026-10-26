---
title: get_MaxBlobsBytesInMemory()
second_title: Riferimento API di Aspose.Slides per C++
description: Definisce la dimensione massima totale (in byte) che tutti i BLOB possono occupare in memoria. Per impostazione predefinita, tutti i BLOB vengono caricati in memoria; solo quando questo limite viene raggiunto vengono utilizzati meccanismi alternativi (come file temporanei). Mantenere i BLOB in memoria massimizza le prestazioni ma può comportare un elevato utilizzo della memoria. Utilizza questa proprietà per adattare il comportamento al tuo ambiente o ai requisiti.
type: docs
weight: 79
url: /it/aspose.slides/blobmanagementoptions/get_maxblobsbytesinmemory/
---
## BlobManagementOptions::get_MaxBlobsBytesInMemory() metodo

Definisce la dimensione massima totale (in byte) che tutti i BLOB possono occupare in memoria. Per impostazione predefinita, tutti i BLOB vengono caricati in memoria; solo quando questo limite viene raggiunto vengono utilizzati meccanismi alternativi (come file temporanei). Mantenere i BLOB in memoria massimizza le prestazioni ma può portare a un elevato utilizzo della memoria. Utilizza questa proprietà per adattare il comportamento al tuo ambiente o ai requisiti.

```cpp
uint64_t Aspose::Slides::BlobManagementOptions::get_MaxBlobsBytesInMemory() override
```

## Osservazioni

Questo valore è ignorato se [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) è impostato su false, poiché la memoria è allora l'unica posizione di archiviazione disponibile e limitare l'uso dei BLOB in memoria non ha alcun effetto.

Il valore predefinito è 629,145,600 byte (600 MB).

È possibile impostare questa proprietà a zero, ma una piccola quantità minima di memoria verrà comunque riservata.

## Vedi anche

* Classe [BlobManagementOptions](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)