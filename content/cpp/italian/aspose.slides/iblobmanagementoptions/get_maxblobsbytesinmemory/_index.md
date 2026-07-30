---
title: get_MaxBlobsBytesInMemory()
second_title: Riferimento API di Aspose.Slides per C++
description: Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. Per impostazione predefinita, tutti i BLOB vengono caricati in memoria; solo quando questo limite viene raggiunto vengono impiegati meccanismi alternativi (come file temporanei). Mantenere i BLOB in memoria massimizza le prestazioni ma può provocare un elevato utilizzo della memoria. Usa questa proprietà per adattare il comportamento al tuo ambiente o ai requisiti.
type: docs
weight: 79
url: /it/aspose.slides/iblobmanagementoptions/get_maxblobsbytesinmemory/
---
## IBlobManagementOptions::get_MaxBlobsBytesInMemory() metodo


Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. Per impostazione predefinita, tutti i BLOB vengono caricati in memoria; solo quando questo limite viene raggiunto vengono impiegati meccanismi alternativi (come file temporanei). Mantenere i BLOB in memoria massimizza le prestazioni ma può provocare un elevato utilizzo della memoria. Usa questa proprietà per adattare il comportamento al tuo ambiente o ai requisiti.

```cpp
virtual uint64_t Aspose::Slides::IBlobManagementOptions::get_MaxBlobsBytesInMemory()=0
```

## Osservazioni


Questo valore viene ignorato se [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) è impostato su false, poiché la memoria è allora l'unica posizione di archiviazione disponibile e limitare l'uso dei BLOB in memoria non ha effetto. 

Il valore predefinito è 629.145.600 byte (600 MB). 

Puoi impostare questa proprietà a zero, ma una piccola quantità minima di memoria verrà comunque riservata. 
## Vedi anche

* Classe [IBlobManagementOptions](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)