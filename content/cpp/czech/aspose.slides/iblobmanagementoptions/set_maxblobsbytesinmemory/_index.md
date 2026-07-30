---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy zabírat v paměti. Ve výchozím nastavení jsou všechny BLOBy načteny do paměti; až po dosažení tohoto limitu jsou použity alternativní mechanismy (například dočasné soubory). Uchovávání BLOBů v paměti maximalizuje výkon, ale může vést k vysokému využití paměti. Použijte tuto vlastnost k přizpůsobení chování vašemu prostředí nebo požadavkům.
type: docs
weight: 92
url: /cs/aspose.slides/iblobmanagementoptions/set_maxblobsbytesinmemory/
---
## IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) metoda


Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy zabírat v paměti. Ve výchozím nastavení jsou všechny BLOBy načteny do paměti; pouze po dosažení tohoto omezení jsou použity alternativní mechanismy (například dočasné soubory). Uchovávání BLOBů v paměti maximalizuje výkon, ale může vést k vysokému využití paměti. Použijte tuto vlastnost k přizpůsobení chování vašemu prostředí nebo požadavkům.

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value)=0
```

## Poznámky


Tato hodnota se ignoruje, pokud je [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) nastaveno na false, protože paměť je pak jediným dostupným úložištěm a omezení používání BLOBů v paměti nemá žádný efekt. 

Výchozí hodnota je 629,145,600 bajtů (600 MB). 

Tuto vlastnost můžete nastavit na nulu, ale stále bude rezervováno malé minimální množství paměti. 
## Viz také

* Třída [IBlobManagementOptions](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)