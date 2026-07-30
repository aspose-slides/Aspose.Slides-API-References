---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides pro C++ referenci API
description: Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBs v paměti zabírat. Ve výchozím nastavení jsou všechny BLOBs načteny do paměti; až po dosažení tohoto limitu jsou použity alternativní mechanismy (například dočasné soubory). Uchovávání BLOBs v paměti maximalizuje výkon, ale může vést k vysoké spotřebě paměti. Použijte tuto vlastnost k přizpůsobení chování vašemu prostředí nebo požadavkům.
type: docs
weight: 92
url: /cs/aspose.slides/blobmanagementoptions/set_maxblobsbytesinmemory/
---
## BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) metoda


Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy obsadit v paměti. Ve výchozím nastavení jsou všechny BLOBy načteny do paměti; až po dosažení tohoto limitu jsou použity alternativní mechanismy (například dočasné soubory). Uchovávání BLOBů v paměti maximalizuje výkon, ale může vést k vysoké spotřebě paměti. Použijte tuto vlastnost k přizpůsobení chování vašemu prostředí nebo požadavkům.

```cpp
void Aspose::Slides::BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value) override
```

## Poznámky


Tato hodnota je ignorována, pokud je [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) nastavena na false, protože paměť je pak jediným dostupným úložištěm a omezení používání BLOBů v paměti nemá žádný účinek. 

Výchozí hodnota je 629,145,600 bajtů (600 MB). 

Tuto vlastnost můžete nastavit na nulu, ale malé minimální množství paměti bude i tak rezervováno. 
## Viz také

* Třída [BlobManagementOptions](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)