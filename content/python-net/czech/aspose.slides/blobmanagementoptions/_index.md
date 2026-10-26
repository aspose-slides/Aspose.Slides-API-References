---
title: BlobManagementOptions class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions třída

Představuje možnosti, které lze použít k řízení pravidel zpracování BLOB a dalších nastavení BLOB.

Typ BlobManagementOptions poskytuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides/blobmanagementoptions/__init__/#) | Vytvoří nové výchozí možnosti správy BLOB. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/cs/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | Tato vlastnost určuje, zda může být instance třídy Presentation vlastníkem zdroje – souboru <br/>            nebo proudu během životnosti instance. Pokud je instance vlastníkem, zamkne zdroj. To pomáhá <br/>            zlepšit spotřebu paměti a výkon při práci s BLOB, ale zdroj (proud nebo soubor) <br/>            nemůže být během životnosti instance Presentation změněn. |
| [`is_temporary_files_allowed`](/slides/python-net/cs/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | Tato vlastnost určuje, zda mohou být během práce s BLOB vytvářeny dočasné soubory, což výrazně <br/>            snižuje spotřebu paměti, ale vyžaduje oprávnění k vytváření souborů.<br/>            Všechny soubory budou po dokončení práce s prezentací smazány. |
| [`temp_files_root_path`](/slides/python-net/cs/aspose.slides/blobmanagementoptions/temp_files_root_path/) | Kořenová cesta, kde budou vytvářeny dočasné soubory. Ve výchozím nastavení bude použita systémová dočasná složka. <br/>            Hostitelský proces by měl mít oprávnění <br/>            k vytváření souborů a složek tam. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/cs/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy zabírat v paměti. Ve výchozím nastavení jsou všechny BLOBy<br/>            načteny do paměti; teprve po dosažení tohoto limitu jsou použity alternativní mechanismy (například dočasné<br/>            soubory). Udržování BLOBů v paměti maximalizuje výkon, ale může vést k vysoké spotřebě paměti. Použijte<br/>            tuto vlastnost k přizpůsobení chování vašemu prostředí nebo požadavkům. |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)