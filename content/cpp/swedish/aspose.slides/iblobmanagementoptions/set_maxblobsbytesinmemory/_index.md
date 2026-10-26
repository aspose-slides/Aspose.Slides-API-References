---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides för C++ API-referens
description: Definierar den maximala totala storleken (i byte) som alla BLOBs får uppta i minnet. Som standard laddas alla BLOBs in i minnet; först när denna gräns nås används alternativa mekanismer (såsom tillfälliga filer). Att hålla BLOBs i minnet maximerar prestanda men kan leda till hög minnesanvändning. Använd denna egenskap för att anpassa beteendet till din miljö eller dina krav.
type: docs
weight: 92
url: /sv/aspose.slides/iblobmanagementoptions/set_maxblobsbytesinmemory/
---
## IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) metod

Definierar den maximala totala storleken (i byte) som alla BLOBs får uppta i minnet. Som standard laddas alla BLOBs in i minnet; först när denna gräns nås används alternativa mekanismer (såsom tillfälliga filer). Att hålla BLOBs i minnet maximerar prestanda men kan leda till hög minnesanvändning. Använd denna egenskap för att anpassa beteendet till din miljö eller dina krav.

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value)=0
```

## Anmärkningar

Detta värde ignoreras om [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) är satt till false, eftersom minnet då är den enda lagringsplats som är tillgänglig och begränsning av BLOB-användning i minnet har ingen effekt.

Standardvärdet är 629,145,600 byte (600 MB).

Du kan sätta denna egenskap till noll, men en liten minsta mängd minne kommer fortfarande att reserveras.

## Se även

* Klass [IBlobManagementOptions](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)