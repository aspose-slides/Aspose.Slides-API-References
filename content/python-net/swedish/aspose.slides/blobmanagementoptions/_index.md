---
title: BlobManagementOptions class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions klass

Representerar alternativ som kan användas för att hantera BLOB-regler och andra BLOB-inställningar.

BlobManagementOptions-typen exponerar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides/blobmanagementoptions/__init__/#) | Skapar nya standardalternativ för blob-hantering. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/sv/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | Denna egenskap definierar om en instans av Presentation-klassen kan vara ägare till käll-filen <br/> eller strömmen under instansens livstid. Om instansen är ägare låser den källan. Detta hjälper <br/> att förbättra minnesanvändning och prestanda när man arbetar med BLOB-objekt, men källan (ström eller fil) <br/> kan inte ändras under Presentation-instansens livstid. |
| [`is_temporary_files_allowed`](/slides/python-net/sv/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | Denna egenskap definierar om temporära filer kan skapas när man arbetar med BLOB-objekt, vilket kraftigt <br/> minskar minnesanvändningen men kräver behörighet att skapa filer.<br/> Alla filer kommer att tas bort när arbetet med presentationen är avslutat. |
| [`temp_files_root_path`](/slides/python-net/sv/aspose.slides/blobmanagementoptions/temp_files_root_path/) | Sökvägen där temporära filer kommer att skapas. Systemets temporära katalog används som standard. <br/> Hostprocessen bör ha behörighet att <br/> skapa filer och mappar där. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/sv/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | Definierar den maximala totala storleken (i byte) som alla BLOB-objekt får uppta i minnet. Som standard laddas alla BLOB-objekt<br/> in i minnet; först när denna gräns nås används alternativa mekanismer (såsom temporära<br/> filer). Att hålla BLOB-objekt i minnet maximerar prestanda men kan leda till hög minnesanvändning. Använd<br/> denna egenskap för att anpassa beteendet efter din miljö eller dina krav. |

### Se även
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)