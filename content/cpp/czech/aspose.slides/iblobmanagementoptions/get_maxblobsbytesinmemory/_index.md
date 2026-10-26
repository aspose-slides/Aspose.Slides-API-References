---
title: get_MaxBlobsBytesInMemory()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Definuje maximální celkovou velikost (v bajtech), kterou všechny BLOBy mohou zabírat v paměti. Ve výchozím nastavení jsou všechny BLOBy načítány do paměti; až po dosažení tohoto limitu jsou použity alternativní mechanismy (například dočasné soubory). Uchovávání BLOBů v paměti maximalizuje výkon, ale může vést k vysoké spotřebě paměti. Použijte tuto vlastnost k přizpůsobení chování vašemu prostředí nebo požadavkům.
type: docs
weight: 79
url: /cs/aspose.slides/iblobmanagementoptions/get_maxblobsbytesinmemory/
---
## IBlobManagementOptions::get_MaxBlobsBytesInMemory() metoda

Definuje maximální celkovou velikost (v bajtech), kterou všechny BLOBy mohou zabírat v paměti. Ve výchozím nastavení jsou všechny BLOBy načítány do paměti; až po dosažení tohoto limitu jsou použity alternativní mechanismy (například dočasné soubory). Uchovávání BLOBů v paměti maximalizuje výkon, ale může vést k vysoké spotřebě paměti. Použijte tuto vlastnost k přizpůsobení chování vašemu prostředí nebo požadavkům.

```cpp
virtual uint64_t Aspose::Slides::IBlobManagementOptions::get_MaxBlobsBytesInMemory()=0
```

## Poznámky

Tato hodnota se ignoruje, pokud je [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) nastaveno na false, protože paměť je pak jediným dostupným úložištěm a omezení používání BLOBů v paměti nemá žádný efekt.  

Výchozí hodnota je 629,145,600 bajtů (600 MB).  

Můžete nastavit tuto vlastnost na nulu, ale malé minimální množství paměti bude i nadále rezervováno. 

## Viz také

* třída [IBlobManagementOptions](../)
* jmenný prostor [Aspose::Slides](../../)
* knihovna [Aspose.Slides](../../../)