---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory tulajdonság
Meghatározza a maximális teljes méretet (bájtban), amelyet az összes BLOB elfoglalhat a memóriában. Alapértelmezés szerint az összes BLOB betöltődik a memóriába; csak akkor, amikor ez a határ elérődik, kerülnek alkalmazásra alternatív mechanizmusok (például ideiglenes fájlok). A BLOB-ok memóriában tartása maximalizálja a teljesítményt, de magas memóriahasználathoz vezethet. Használja ezt a tulajdonságot a viselkedés környezetéhez vagy igényeihez igazításához.


### Megjegyzések

Ez a tulajdonság figyelmen kívül marad, ha [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/hu/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) hamis értékre van állítva, mivel ebben az esetben a memória az egyetlen elérhető tárolási hely, és a memóriában lévő BLOB használat korlátozása nem hatásos.

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
* osztály [`IBlobManagementOptions`](/slides/python-net/hu/aspose.slides/iblobmanagementoptions)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)