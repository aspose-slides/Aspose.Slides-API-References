---
title: get_MaxBlobsBytesInMemory()
second_title: Aspose.Slides för C++ API-referens
description: Definierar den maximala totala storleken (i byte) som alla BLOBs får uppta i minnet. Som standard laddas alla BLOBs in i minnet; först när denna gräns nås används alternativa mekanismer (t.ex. temporära filer). Att behålla BLOBs i minnet maximerar prestanda men kan leda till hög minnesanvändning. Använd denna egenskap för att anpassa beteendet efter din miljö eller dina krav.
type: docs
weight: 79
url: /sv/aspose.slides/blobmanagementoptions/get_maxblobsbytesinmemory/
---
## BlobManagementOptions::get_MaxBlobsBytesInMemory() metod

Definierar den maximala totala storleken (i byte) som alla BLOBs får uppta i minnet. Som standard laddas alla BLOBs in i minnet; först när denna gräns nås används alternativa mekanismer (såsom temporära filer). Att behålla BLOBs i minnet maximerar prestanda men kan leda till hög minnesanvändning. Använd den här egenskapen för att anpassa beteendet till din miljö eller dina krav.

```cpp
uint64_t Aspose::Slides::BlobManagementOptions::get_MaxBlobsBytesInMemory() override
```

## Anmärkningar

Detta värde ignoreras om [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) är satt till false, eftersom minnet då är den enda tillgängliga lagringsplatsen och begränsning av BLOB-användning i minnet inte har någon effekt. 

Standardvärdet är 629,145,600 byte (600 MB). 

Du kan sätta den här egenskapen till noll, men ett litet minimum av minne kommer fortfarande att reserveras. 

## Se även

* Klass [BlobManagementOptions](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)