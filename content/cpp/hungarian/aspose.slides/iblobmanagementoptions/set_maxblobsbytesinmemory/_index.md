---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides for C++ API referencia
description: Meghatározza a maximális teljes méretet (bájtban), amelyet az összes BLOB elfoglalhat a memóriában. Alapértelmezés szerint az összes BLOB a memóriába töltődik; csak akkor, amikor ez a határ elérődik, kerülnek alkalmazásra alternatív mechanizmusok (például ideiglenes fájlok). A BLOB-ok memóriában tartása maximalizálja a teljesítményt, de nagy memóriahasználathoz vezethet. Használja ezt a tulajdonságot a viselkedés a környezetéhez vagy követelményeihez igazításához.
type: docs
weight: 92
url: /hu/aspose.slides/iblobmanagementoptions/set_maxblobsbytesinmemory/
---
## IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) metódus


Meghatározza a maximális teljes méretet (bájtban), amelyet az összes BLOB elfoglalhat a memóriában. Alapértelmezés szerint az összes BLOB a memóriába töltődik; csak akkor, amikor ez a határ elérődik, kerülnek alkalmazásra alternatív mechanizmusok (például ideiglenes fájlok). A BLOB-ok memóriában tartása maximalizálja a teljesítményt, de nagy memóriahasználathoz vezethet. Használja ezt a tulajdonságot a viselkedés a környezetéhez vagy követelményeihez igazításához.

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value)=0
```

## Megjegyzés


Ez az érték figyelmen kívül marad, ha a [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) hamisra van állítva, mivel ekkor a memória az egyetlen rendelkezésre álló tárolóhely, és az in-memory BLOB használat korlátozása nincs hatással. 

Az alapértelmezett érték 629,145,600 bájt (600 MB). 

Beállíthatja ezt a tulajdonságot nullára, de egy kis minimális memória mennyiség továbbra is lefoglalásra kerül. 
## Lásd még

* Osztály [IBlobManagementOptions](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)