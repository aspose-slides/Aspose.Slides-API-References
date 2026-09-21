---
title: IBlobManagementOptions class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions klasse

Een Binary Large Object (BLOB) is binaire data opgeslagen als één entiteit - dwz. BLOB kan een 
            audio-, video- of presentatie-bestand zelf zijn. Er worden verschillende technieken gebruikt om het geheugengebruik te optimaliseren 
            bij het werken met BLOB's - die al in de presentatie waren opgeslagen of later programmatisch kunnen worden toegevoegd. 
            Met [`IBlobManagementOptions`](/slides/python-net/nl/aspose.slides/iblobmanagementoptions) kun je verschillende gedragsaspecten met betrekking tot het omgaan met BLOB's 
            aanpassen voor de levensduur van de [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation) instantie.

The IBlobManagementOptions type exposes the following members:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/nl/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | Deze eigenschap bepaalt of een instantie van de Presentation-klasse eigenaar kan zijn van het bron-bestand <br/>            of -stream gedurende de levensduur van de instantie. Als de instantie een eigenaar is, vergrendelt deze de bron. Dit helpt <br/>            het geheugengebruik en de prestaties te verbeteren bij het werken met BLOB's, maar de bron (stream of bestand) <br/>            kan niet worden gewijzigd gedurende de levensduur van de Presentation-instantie. Dit is een voorbeeld: |
| [`is_temporary_files_allowed`](/slides/python-net/nl/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | Deze eigenschap bepaalt of tijdelijke bestanden kunnen worden aangemaakt tijdens het werken met BLOB's, wat het geheugengebruik sterk <br/>            vermindert maar permissies vereist om bestanden te maken.<br/>            Alle bestanden worden verwijderd nadat het werk met de presentatie is voltooid. |
| [`temp_files_root_path`](/slides/python-net/nl/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | Het hoofdpad waar tijdelijke bestanden worden aangemaakt. Standaard wordt de systeem-tijdelijke map gebruikt. <br/>            Het host-proces moet permissies hebben om <br/>            bestanden en mappen daar aan te maken. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/nl/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | Definieert de maximale totale grootte (in bytes) die alle BLOB's in het geheugen mogen innemen. Standaard worden alle BLOB's<br/>            in het geheugen geladen; pas wanneer deze limiet is bereikt, worden alternatieve mechanismen (zoals tijdelijke<br/>            bestanden) ingezet. Het behouden van BLOB's in het geheugen maximaliseert prestaties maar kan leiden tot hoog geheugengebruik. Gebruik<br/>            deze eigenschap om het gedrag af te stemmen op uw omgeving of eisen. |


### Zie ook
* klasse [`IBlobManagementOptions`](/slides/python-net/nl/aspose.slides/iblobmanagementoptions)
* klasse [`IPresentation`](/slides/python-net/nl/aspose.slides/ipresentation)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)