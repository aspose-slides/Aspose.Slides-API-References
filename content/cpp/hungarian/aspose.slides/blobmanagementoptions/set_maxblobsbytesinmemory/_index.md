---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides C++ API referenciája
description: Meghatározza a maximális összméretet (bájtban), amelyet az összes BLOB a memóriában foglalhat el. Alapértelmezés szerint minden BLOB memóriába kerül; csak akkor alkalmaznak alternatív mechanizmusokat (például ideiglenes fájlokat), ha ez a határ eléri. A BLOB-ok memóriában tartása maximalizálja a teljesítményt, de magas memóriahasználathoz vezethet. Használja ezt a tulajdonságot, hogy a viselkedést a környezetéhez vagy követelményeihez igazítsa.
type: docs
weight: 92
url: /hu/aspose.slides/blobmanagementoptions/set_maxblobsbytesinmemory/
---
## BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) metódus

Defines the maximum total size (in bytes) that all BLOBs may occupy in memory. By default, all BLOBs are loaded into memory; only once this limit is reached are alternative mechanisms (such as temporary files) employed. Keeping BLOBs in memory maximizes performance but can lead to high memory usage. Use this property to tailor behavior to your environment or requirements.

```cpp
void Aspose::Slides::BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value) override
```

## Megjegyzések

This value is ignored if [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) is set to false, since memory is then the only storage location available and limiting in-memory BLOB usage has no effect. 

The default value is 629,145,600 bytes (600 MB). 

You may set this property to zero, but a small minimum amount of memory will still be reserved. 

## Lásd még

* Osztály [BlobManagementOptions](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)