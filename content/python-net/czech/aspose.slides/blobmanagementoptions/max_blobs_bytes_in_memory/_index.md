---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides pro Python přes .NET API reference
description: 
type: docs
url: /cs/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory vlastnost
Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy zabírat v paměti. Ve výchozím nastavení jsou všechny BLOBy načteny do paměti; až po dosažení tohoto limitu jsou použity alternativní mechanismy (například dočasné soubory). Udržování BLOBů v paměti maximalizuje výkon, ale může vést k vysoké spotřebě paměti. Použijte tuto vlastnost k přizpůsobení chování vašemu prostředí nebo požadavkům.


### Poznámky

Tato vlastnost je ignorována, pokud je [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/cs/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) nastaveno na false, protože paměť je pak jediným dostupným úložištěm a omezení používání BLOBů v paměti nemá žádný účinek.

### Definice:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```


### Viz také
* třída [`BlobManagementOptions`](/slides/python-net/cs/aspose.slides/blobmanagementoptions)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)