---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory egenskap
Definierar den maximala totala storleken (i byte) som alla BLOBs kan uppta i minnet. Som standard laddas alla BLOBs in i minnet; först när denna gräns nås används alternativa mekanismer (såsom temporära filer). Att hålla BLOBs i minnet maximerar prestanda men kan leda till hög minnesanvändning. Använd denna egenskap för att anpassa beteendet efter din miljö eller dina krav.


### Anmärkningar

Denna egenskap ignoreras om [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/sv/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) är satt till false, eftersom minnet då är den enda tillgängliga lagringsplatsen och begränsning av BLOB-användning i minnet inte har någon effekt.

### Definition:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```


### Se också
* klass [`IBlobManagementOptions`](/slides/python-net/sv/aspose.slides/iblobmanagementoptions)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)