---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory egenskap
Definierar den maximala totala storleken (i byte) som alla BLOBs får uppta i minnet. Som standard laddas alla BLOBs in i minnet; först när denna gräns nås används alternativa mekanismer (såsom temporära filer). Att behålla BLOBs i minnet maximerar prestanda men kan leda till hög minnesanvändning. Använd denna egenskap för att anpassa beteendet efter din miljö eller dina krav.

### Anmärkningar
Denna egenskap ignoreras om [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/sv/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) är satt till false, eftersom minnet då är den enda lagringsplatsen som är tillgänglig och begränsning av BLOB-användning i minnet har ingen effekt.

### Definition:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```

### Se även
* klass [`BlobManagementOptions`](/slides/python-net/sv/aspose.slides/blobmanagementoptions)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)