---
title: get_MaxBlobsBytesInMemory()
second_title: Aspose.Slides pro referenci API C++
description: Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBs zabírat v paměti. Ve výchozím nastavení jsou všechny BLOBs načteny do paměti; až když je tento limit dosažen, jsou použity alternativní mechanismy (například dočasné soubory). Udržování BLOBs v paměti maximalizuje výkon, ale může vést k vysoké spotřebě paměti. Použijte tuto vlastnost k přizpůsobení chování vašemu prostředí nebo požadavkům.
type: docs
weight: 79
url: /cs/aspose.slides/blobmanagementoptions/get_maxblobsbytesinmemory/
---
## BlobManagementOptions::get_MaxBlobsBytesInMemory() metoda

Definuje maximální celkovou velikost (v bajtech), kterou všechny BLOBs mohou zabírat v paměti. Ve výchozím nastavení jsou všechny BLOBs načteny do paměti; až když je tento limit dosažen, jsou použity alternativní mechanismy (například dočasné soubory). Udržování BLOBs v paměti maximalizuje výkon, ale může vést k vysoké spotřebě paměti. Použijte tuto vlastnost k přizpůsobení chování vašemu prostředí nebo požadavkům.

```cpp
uint64_t Aspose::Slides::BlobManagementOptions::get_MaxBlobsBytesInMemory() override
```

## Poznámky

Tato hodnota je ignorována, pokud je [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) nastaveno na false, protože paměť je pak jediným dostupným úložištěm a omezení používání BLOB v paměti nemá žádný efekt.

Výchozí hodnota je 629,145,600 bajtů (600 MB).

Můžete nastavit tuto vlastnost na nulu, ale stále bude rezervováno malé minimální množství paměti.

## Viz také

* Třída [BlobManagementOptions](../)
* Prostor názvů [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)