---
title: set_MaxBlobsBytesInMemory()
second_title: Riferimento API Aspose.Slides per C++
description: Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. Per impostazione predefinita, tutti i BLOB sono caricati in memoria; solo quando questo limite viene raggiunto vengono impiegati meccanismi alternativi (come file temporanei). Mantenere i BLOB in memoria massimizza le prestazioni ma può portare a un elevato utilizzo della memoria. Utilizza questa proprietà per adattare il comportamento al tuo ambiente o alle tue esigenze.
type: docs
weight: 92
url: /it/aspose.slides/iblobmanagementoptions/set_maxblobsbytesinmemory/
---
## IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) metodo

Definisce la dimensione totale massima (in byte) che tutti i BLOB possono occupare in memoria. Per impostazione predefinita, tutti i BLOB sono caricati in memoria; solo quando questo limite viene raggiunto vengono impiegati meccanismi alternativi (come file temporanei). Mantenere i BLOB in memoria massimizza le prestazioni ma può portare a un alto utilizzo di memoria. Usa questa proprietà per adattare il comportamento al tuo ambiente o ai tuoi requisiti.

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value)=0
```

## Osservazioni

Questo valore viene ignorato se [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) è impostato su false, poiché la memoria è allora l'unica posizione di archiviazione disponibile e limitare l'uso dei BLOB in memoria non ha effetto.

Il valore predefinito è 629.145.600 byte (600 MB).

È possibile impostare questa proprietà a zero, ma verrà comunque riservata una piccola quantità minima di memoria.

## Vedi anche

* Classe [IBlobManagementOptions](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)