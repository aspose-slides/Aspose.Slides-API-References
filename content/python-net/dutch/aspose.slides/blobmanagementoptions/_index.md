---
title: BlobManagementOptions class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions klasse

Stelt opties voor die kunnen worden gebruikt om BLOB-beheerregels en andere BLOB-instellingen te beheren.

Het type BlobManagementOptions biedt de volgende leden weer:

## Constructoren

| Constructor | Beschrijving |
| :- | :- |
| [`__init__(self)`](/slides/python-net/nl/aspose.slides/blobmanagementoptions/__init__/#) | Maakt nieuwe standaard blob-beheeropties aan. |

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/nl/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | Deze eigenschap bepaalt of een instantie van de Presentation-klasse eigenaar kan zijn van de bron - bestand <br/>            of stream gedurende de levensduur van de instantie. Als de instantie eigenaar is, vergrendelt deze de bron. Dit helpt <br/>            het geheugenverbruik en de prestaties te verbeteren bij het werken met BLOB's, maar de bron (stream of bestand) <br/>            kan niet worden gewijzigd gedurende de levensduur van de Presentation-instantie. |
| [`is_temporary_files_allowed`](/slides/python-net/nl/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | Deze eigenschap bepaalt of tijdelijke bestanden kunnen worden aangemaakt tijdens het werken met BLOB's, wat het geheugenverbruik aanzienlijk <br/>            vermindert, maar toestemming vereist om bestanden te creëren.<br/>            Alle bestanden worden verwijderd nadat het werken met de presentatie is voltooid. |
| [`temp_files_root_path`](/slides/python-net/nl/aspose.slides/blobmanagementoptions/temp_files_root_path/) | Het hoofdpad waar tijdelijke bestanden worden aangemaakt. Standaard wordt de systeem-tijdelijke map gebruikt. <br/>            Het host-proces moet toestemming hebben om <br/>            bestanden en mappen daar te maken. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/nl/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | Bepaalt de maximale totale grootte (in bytes) die alle BLOB's in het geheugen mogen innemen. Standaard worden alle BLOB's<br/>            in het geheugen geladen; pas wanneer deze limiet is bereikt, worden alternatieve mechanismen (zoals tijdelijke<br/>            bestanden) ingezet. Het houden van BLOB's in het geheugen maximaliseert de prestaties, maar kan leiden tot hoog geheugenverbruik. Gebruik<br/>            deze eigenschap om het gedrag aan te passen aan uw omgeving of vereisten. |

### Zie ook
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)