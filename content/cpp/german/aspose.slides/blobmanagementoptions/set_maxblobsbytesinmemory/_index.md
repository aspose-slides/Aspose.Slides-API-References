---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides für C++ API-Referenz
description: Definiert die maximale Gesamtgröße (in Bytes), die alle BLOBs im Speicher belegen dürfen. Standardmäßig werden alle BLOBs in den Speicher geladen; erst wenn dieses Limit erreicht ist, werden alternative Mechanismen (wie temporäre Dateien) eingesetzt. Das Halten von BLOBs im Speicher maximiert die Leistung, kann jedoch zu hohem Speicherverbrauch führen. Verwenden Sie diese Eigenschaft, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen.
type: docs
weight: 92
url: /de/aspose.slides/blobmanagementoptions/set_maxblobsbytesinmemory/
---
## BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) Methode

Definiert die maximale Gesamtegröße (in Bytes), die alle BLOBs im Speicher belegen dürfen. Standardmäßig werden alle BLOBs in den Speicher geladen; erst wenn dieses Limit erreicht ist, werden alternative Mechanismen (wie temporäre Dateien) eingesetzt. Das Halten von BLOBs im Speicher maximiert die Leistung, kann jedoch zu hohem Speicherverbrauch führen. Verwenden Sie diese Eigenschaft, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen.

```cpp
void Aspose::Slides::BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value) override
```

## Hinweise

Dieser Wert wird ignoriert, wenn [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) auf false gesetzt ist, da der Speicher dann der einzige verfügbare Speicherort ist und das Begrenzen der im Speicher befindlichen BLOB-Nutzung keine Wirkung hat.

Der Standardwert ist 629,145,600 Bytes (600 MB).

Sie können diese Eigenschaft auf Null setzen, aber ein kleiner minimaler Speicherbetrag wird weiterhin reserviert.

## Siehe auch

* Klasse [BlobManagementOptions](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)