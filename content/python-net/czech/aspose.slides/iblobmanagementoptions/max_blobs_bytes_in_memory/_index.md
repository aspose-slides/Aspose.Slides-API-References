---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory vlastnost
Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy zabírat v paměti. Ve výchozím nastavení jsou všechny BLOBy načteny do paměti; až když je tento limit dosažen, jsou použity alternativní mechanismy (např. dočasné soubory). Uchovávání BLOBů v paměti maximalizuje výkon, ale může vést k vysoké spotřebě paměti. Použijte tuto vlastnost k přizpůsobení chování vašemu prostředí nebo požadavkům.

### Poznámky

Tato vlastnost je ignorována, pokud je [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/cs/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) nastaveno na false, protože paměť je pak jediným dostupným úložištěm a omezení používání BLOBů v paměti nemá žádný vliv.

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
* třída [`IBlobManagementOptions`](/slides/python-net/cs/aspose.slides/iblobmanagementoptions)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)