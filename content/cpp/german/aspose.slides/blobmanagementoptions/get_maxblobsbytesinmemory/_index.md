---
title: get_MaxBlobsBytesInMemory()
second_title: Aspose.Slides für C++ API-Referenz
description: Definiert die maximale Gesamtspeichermenge (in Bytes), die alle BLOBs im Speicher belegen dürfen. Standardmäßig werden alle BLOBs in den Speicher geladen; erst wenn diese Grenze erreicht ist, werden alternative Mechanismen (wie temporäre Dateien) eingesetzt. Das Beibehalten von BLOBs im Speicher maximiert die Leistung, kann jedoch zu hohem Speicherverbrauch führen. Verwenden Sie diese Eigenschaft, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen.
type: docs
weight: 79
url: /de/aspose.slides/blobmanagementoptions/get_maxblobsbytesinmemory/
---
## BlobManagementOptions::get_MaxBlobsBytesInMemory() Methode


Definiert die maximale Gesamtgröße (in Bytes), die alle BLOBs im Speicher belegen dürfen. Standardmäßig werden alle BLOBs in den Speicher geladen; erst wenn diese Grenze erreicht ist, werden alternative Mechanismen (wie temporäre Dateien) eingesetzt. Das Beibehalten von BLOBs im Speicher maximiert die Leistung, kann jedoch zu hohem Speicherverbrauch führen. Verwenden Sie diese Eigenschaft, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen.

```cpp
uint64_t Aspose::Slides::BlobManagementOptions::get_MaxBlobsBytesInMemory() override
```

## Hinweise


Dieser Wert wird ignoriert, wenn [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) auf false gesetzt ist, da der Speicher dann der einzige verfügbare Speicherort ist und das Begrenzen der in-Speicher-BLOB-Nutzung keine Wirkung hat. 

Der Standardwert beträgt 629,145,600 Bytes (600 MB). 

Sie können diese Eigenschaft auf null setzen, aber ein kleiner Mindestwert an Speicher wird weiterhin reserviert. 
## Siehe auch

* Klasse [BlobManagementOptions](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)