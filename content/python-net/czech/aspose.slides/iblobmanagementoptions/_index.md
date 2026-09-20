---
title: IBlobManagementOptions class
second_title: Aspose.Slides pro Python přes .NET referenční příručku API
description: 
type: docs
url: /cs/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions třída

Binární velký objekt (BLOB) je binární data uložená jako jediné celku - tj. BLOB může být audio, video nebo samotná prezentace. Používá se řada technik pro optimalizaci spotřeby paměti při práci s BLOBy - které již byly uloženy v prezentaci nebo jsou později přidány programově. Pomocí [`IBlobManagementOptions`](/slides/python-net/cs/aspose.slides/iblobmanagementoptions) můžete změnit různé aspekty chování při zpracování BLOBů pro životnost instance [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation).

The IBlobManagementOptions type exposes the following members:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/cs/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | Tato vlastnost určuje, zda může být instance třídy Presentation vlastníkem zdroje – souboru <br/> nebo proudu během životnosti instance. Pokud je instance vlastníkem, zamkne zdroj. To pomáhá <br/> zlepšit spotřebu paměti a výkon při práci s BLOBy, ale zdroj (proud nebo soubor) <br/> nemůže být během životnosti instance Presentation změněn. Toto je příklad: |
| [`is_temporary_files_allowed`](/slides/python-net/cs/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | Tato vlastnost určuje, zda mohou být během práce s BLOBy vytvářeny dočasné soubory, což výrazně <br/> snižuje spotřebu paměti, ale vyžaduje oprávnění k vytváření souborů.<br/> Všechny soubory budou po dokončení práce s prezentací smazány. |
| [`temp_files_root_path`](/slides/python-net/cs/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | Kořenová cesta, kam budou vytvářeny dočasné soubory. Ve výchozím nastavení bude použita systémová dočasná složka. <br/> Hostitelský proces by měl mít oprávnění <br/> k vytváření souborů a složek zde. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/cs/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | Určuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy zabírat v paměti. Ve výchozím nastavení jsou všechny BLOBy<br/> načteny do paměti; až po dosažení tohoto limitu jsou použity alternativní mechanismy (například dočasné<br/> soubory). Uchovávání BLOBů v paměti maximalizuje výkon, ale může vést k vysoké spotřebě paměti. Použijte<br/> tuto vlastnost k přizpůsobení chování vašemu prostředí nebo požadavkům. |

### Viz také
* třída [`IBlobManagementOptions`](/slides/python-net/cs/aspose.slides/iblobmanagementoptions)
* třída [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)