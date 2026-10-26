---
title: set_MaxBlobsBytesInMemory()
second_title: Riferimento API Aspose.Slides per C++
description: Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. Per impostazione predefinita, tutti i BLOB sono caricati in memoria; solo quando questo limite viene raggiunto vengono impiegati meccanismi alternativi (come i file temporanei). Mantenere i BLOB in memoria massimizza le prestazioni ma può comportare un elevato consumo di memoria. Utilizza questa proprietà per adattare il comportamento al tuo ambiente o alle tue esigenze.
type: docs
weight: 92
url: /it/aspose.slides/blobmanagementoptions/set_maxblobsbytesinmemory/
---
## BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) metodo

Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. Per impostazione predefinita, tutti i BLOB sono caricati in memoria; solo quando questo limite viene raggiunto vengono utilizzati meccanismi alternativi (come i file temporanei). Mantenere i BLOB in memoria massimizza le prestazioni ma può portare a un elevato consumo di memoria. Utilizza questa proprietà per adattare il comportamento al tuo ambiente o alle tue esigenze.

```cpp
void Aspose::Slides::BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value) override
```

## Osservazioni

Questo valore è ignorato se [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) è impostato a false, poiché la memoria è allora l'unica posizione di archiviazione disponibile e limitare l'uso dei BLOB in memoria non ha effetto. 

Il valore predefinito è 629,145,600 byte (600 MB). 

È possibile impostare questa proprietà a zero, ma una piccola quantità minima di memoria sarà comunque riservata. 

## Vedi anche

* Classe [BlobManagementOptions](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)