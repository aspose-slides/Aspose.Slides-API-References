---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides för C++ API-referens
description: Definierar den maximala totala storleken (i byte) som alla BLOBs får uppta i minnet. Som standard laddas alla BLOBs in i minnet; först när denna gräns nås används alternativa mekanismer (såsom temporära filer). Att hålla BLOBs i minnet maximerar prestanda men kan leda till hög minnesanvändning. Använd den här egenskapen för att anpassa beteendet efter din miljö eller dina krav.
type: docs
weight: 92
url: /sv/aspose.slides/blobmanagementoptions/set_maxblobsbytesinmemory/
---
## BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) metod

Definierar den maximala totala storleken (i byte) som alla BLOBs får uppta i minnet. Som standard laddas alla BLOBs in i minnet; först när denna gräns nås används alternativa mekanismer (såsom temporära filer). Att hålla BLOBs i minnet maximerar prestanda men kan leda till hög minnesanvändning. Använd den här egenskapen för att anpassa beteendet efter din miljö eller dina krav.

```cpp
void Aspose::Slides::BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value) override
```

## Anmärkningar

Detta värde ignoreras om [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) är satt till false, eftersom minnet då är den enda tillgängliga lagringsplatsen och begränsning av BLOB-användning i minnet har ingen effekt.

Standardvärdet är 629,145,600 byte (600 MB).

Du kan sätta den här egenskapen till noll, men en liten minsta mängd minne kommer fortfarande att reserveras.
## Se också

* Klass [BlobManagementOptions](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)