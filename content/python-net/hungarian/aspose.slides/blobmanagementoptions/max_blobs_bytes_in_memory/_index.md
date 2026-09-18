---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides a Pythonhoz .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory tulajdonság
Meghatározza a maximális összméretet (bájtban), amelyet az összes BLOB elfoglalhat a memóriában. Alapértelmezetten az összes BLOB a memóriába töltődik be; csak amikor ez a korlát eléri, kerülnek alkalmazásra alternatív mechanizmusok (például ideiglenes fájlok). A BLOB-ok memóriában tartása maximalizálja a teljesítményt, de magas memóriahasználathoz vezethet. Használja ezt a tulajdonságot a viselkedés testreszabásához a környezetéhez vagy követelményeihez.

### Megjegyzés
Ez a tulajdonság figyelmen kívül marad, ha [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/hu/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) hamisra van állítva, mivel ekkor a memória az egyetlen rendelkezésre álló tárolóhely, és a memóriában lévő BLOB használat korlátozásának nincs hatása.

### Definíció:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```

### Lásd még
* osztály [`BlobManagementOptions`](/slides/python-net/hu/aspose.slides/blobmanagementoptions)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)