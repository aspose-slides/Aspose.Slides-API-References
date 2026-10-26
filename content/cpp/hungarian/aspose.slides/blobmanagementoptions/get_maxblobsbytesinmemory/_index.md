---
title: get_MaxBlobsBytesInMemory()
second_title: Aspose.Slides C++ API Referenciája
description: Meghatározza a maximális teljes méretet (bájtban), amelyet az összes BLOB a memóriában elfoglalhat. Alapértelmezés szerint az összes BLOB betöltődik a memóriába; csak akkor alkalmaznak alternatív mechanizmusokat (például átmeneti fájlok), amikor ez a határ eléri. A BLOB-ok memóriában tartása maximalizálja a teljesítményt, de nagy memóriahasználathoz vezethet. Használja ezt a tulajdonságot a viselkedés környezethez vagy követelményekhez való igazításához.
type: docs
weight: 79
url: /hu/aspose.slides/blobmanagementoptions/get_maxblobsbytesinmemory/
---
## BlobManagementOptions::get_MaxBlobsBytesInMemory() metódus


Meghatározza a maximális teljes méretet (bájtban), amelyet az összes BLOB elfoglalhat a memóriában. Alapértelmezés szerint az összes BLOB betöltődik a memóriába; csak akkor alkalmaznak alternatív mechanizmusokat (például átmeneti fájlok), amikor ez a korlát eléri. A BLOB-ok memóriában tartása maximalizálja a teljesítményt, de nagy memóriahasználathoz vezethet. Használja ezt a tulajdonságot a viselkedés környezethez vagy követelményekhez való igazításához.

```cpp
uint64_t Aspose::Slides::BlobManagementOptions::get_MaxBlobsBytesInMemory() override
```

## Megjegyzés


Ez az érték figyelmen kívül marad, ha [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) hamisra van állítva, mivel ilyenkor a memória az egyetlen rendelkezésre álló tárolóhely, és az in-memory BLOB használat korlátozása hatástalan. 

Az alapértelmezett érték 629 145 600 bájt (600 MB). 

A tulajdonság nullára állítható, de egy kis minimális memória mennyiség továbbra is le lesz foglalva. 
## Lásd még

* Osztály [BlobManagementOptions](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)