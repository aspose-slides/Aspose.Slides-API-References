---
title: IBlobManagementOptions class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions klass

A Binary Large Object (BLOB) är binär data lagrad som en enhet – dvs. BLOB kan vara ett 
            ljud, video eller själva presentationen. Ett antal tekniker används för att optimera minnesanvändning 
            när man arbetar med BLOBs – som redan lagrats i presentationen eller läggs till senare programmässigt. 
            Med [`IBlobManagementOptions`](/slides/python-net/sv/aspose.slides/iblobmanagementoptions) kan du ändra olika beteendeaspekter kring BLOBs 
            hantering för [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation) instansens livstid.

IBlobManagementOptions-typen exponerar följande medlemmar:

## Egenskaper

| Property | Description |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/sv/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | Denna egenskap definierar om en instans av Presentation-klass kan vara ägare av källan – fil <br/>            eller ström under instansens livstid. Om instansen är en ägare låser den källan. Detta hjälper <br/>            att förbättra minnesanvändning och prestanda när man arbetar med BLOBs, men källan (ström eller fil) <br/>            kan inte ändras under Presentation-instansens livstid. Detta är ett exempel: |
| [`is_temporary_files_allowed`](/slides/python-net/sv/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | Denna egenskap definierar om tillfälliga filer kan skapas när man arbetar med BLOBs, vilket kraftigt <br/>            minskar minnesanvändningen men kräver behörighet att skapa filer.<br/>            Alla filer kommer att tas bort när arbetet med presentationen är färdigt. |
| [`temp_files_root_path`](/slides/python-net/sv/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | Rotkatalogen där tillfälliga filer kommer att skapas. Systemets temporära katalog används som standard. <br/>            Värdprocessen bör ha behörighet att <br/>            skapa filer och mappar där. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/sv/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | Definierar den maximala totala storleken (i byte) som alla BLOBs kan uppta i minnet. Som standard laddas alla BLOBs<br/>            in i minnet; först när denna gräns nås används alternativa mekanismer (såsom tillfälliga<br/>            filer). Att hålla BLOBs i minnet maximerar prestanda men kan leda till hög minnesanvändning. Använd<br/>            denna egenskap för att anpassa beteendet efter din miljö eller dina krav. |

### Se även
* klass [`IBlobManagementOptions`](/slides/python-net/sv/aspose.slides/iblobmanagementoptions)
* klass [`IPresentation`](/slides/python-net/sv/aspose.slides/ipresentation)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)