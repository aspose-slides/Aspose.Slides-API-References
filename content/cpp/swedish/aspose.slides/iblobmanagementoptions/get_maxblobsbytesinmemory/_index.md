---
title: get_MaxBlobsBytesInMemory()
second_title: Aspose.Slides för C++ API-referens
description: Definierar den maximala totala storleken (i byte) som alla BLOBs kan uppta i minnet. Som standard laddas alla BLOBs in i minnet; först när denna gräns nås används alternativa mekanismer (t.ex. temporära filer). Att hålla BLOBs i minnet maximerar prestanda men kan leda till hög minnesanvändning. Använd den här egenskapen för att anpassa beteendet till din miljö eller dina krav.
type: docs
weight: 79
url: /sv/aspose.slides/iblobmanagementoptions/get_maxblobsbytesinmemory/
---
## IBlobManagementOptions::get_MaxBlobsBytesInMemory() metod


Definierar den maximala totala storleken (i byte) som alla BLOBs kan uppta i minnet. Som standard laddas alla BLOBs in i minnet; först när denna gräns uppnås används alternativa mekanismer (t.ex. temporära filer). Att hålla BLOBs i minnet maximerar prestanda men kan leda till hög minnesanvändning. Använd den här egenskapen för att anpassa beteendet till din miljö eller dina krav.

```cpp
virtual uint64_t Aspose::Slides::IBlobManagementOptions::get_MaxBlobsBytesInMemory()=0
```

## Anmärkningar


Detta värde ignoreras om [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) är inställt på false, eftersom minnet då är den enda tillgängliga lagringsplatsen och begränsning av BLOB-användning i minnet har ingen effekt.

Standardvärdet är 629,145,600 byte (600 MB).

Du kan sätta denna egenskap till noll, men en liten minsta mängd minne kommer fortfarande att reserveras. 
## Se även

* Klass [IBlobManagementOptions](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)