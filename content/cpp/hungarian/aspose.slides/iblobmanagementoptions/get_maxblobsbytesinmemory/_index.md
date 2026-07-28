---
title: get_MaxBlobsBytesInMemory()
second_title: Aspose.Slides C++ API referencia
description: Meghatározza a maximális összméretet (bájtban), amelyet az összes BLOB a memóriában elfoglalhat. Alapértelmezés szerint az összes BLOB a memóriába töltődik; csak akkor alkalmaznak alternatív mechanizmusokat (például ideiglenes fájlokat), amikor ez a határ elérve van. A BLOB-ok memóriában tartása maximalizálja a teljesítményt, de magas memóriahasználathoz vezethet. Használja ezt a tulajdonságot a viselkedés környezethez vagy követelményekhez való igazításához.
type: docs
weight: 79
url: /hu/aspose.slides/iblobmanagementoptions/get_maxblobsbytesinmemory/
---
## IBlobManagementOptions::get_MaxBlobsBytesInMemory() metódus

Meghatározza a maximális összméretet (bájtban), amelyet az összes BLOB elfoglalhat a memóriában. Alapértelmezés szerint az összes BLOB a memóriába töltődik; csak akkor kerülnek alkalmazásra alternatív mechanizmusok (például ideiglenes fájlok), amikor ez a határ elérve van. A BLOB-okat a memóriában tartva a teljesítmény maximális, de magas memóriahasználathoz vezethet. Használja ezt a tulajdonságot, hogy a viselkedést környezetéhez vagy követelményeihez igazítsa.

```cpp
virtual uint64_t Aspose::Slides::IBlobManagementOptions::get_MaxBlobsBytesInMemory()=0
```

## Megjegyzések

Ez az érték figyelmen kívül marad, ha [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) hamisra van állítva, mivel ilyenkor a memória az egyetlen elérhető tárolóhely, és a memóriában lévő BLOB használat korlátozása nem járhat hatással. 

Az alapértelmezett érték 629,145,600 bájt (600 MB). 

Beállíthatja ezt a tulajdonságot nullára, de egy kis minimális mennyiségű memória továbbra is lefoglalásra kerül. 
## Lásd még

* Osztály [IBlobManagementOptions](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)