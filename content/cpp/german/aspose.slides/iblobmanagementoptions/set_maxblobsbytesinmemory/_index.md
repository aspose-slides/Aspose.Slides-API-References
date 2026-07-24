---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides für C++ API-Referenz
description: Definiert die maximale Gesamtsgröße (in Bytes), die alle BLOBs im Speicher belegen dürfen. Standardmäßig werden alle BLOBs in den Speicher geladen; erst wenn diese Grenze erreicht ist, werden alternative Mechanismen (wie temporäre Dateien) eingesetzt. Das Halten von BLOBs im Speicher maximiert die Leistung, kann jedoch zu hohem Speicherverbrauch führen. Verwenden Sie diese Eigenschaft, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen.
type: docs
weight: 92
url: /de/aspose.slides/iblobmanagementoptions/set_maxblobsbytesinmemory/
---
## IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) Methode

Definiert die maximale Gesamtsgröße (in Bytes), die alle BLOBs im Speicher belegen dürfen. Standardmäßig werden alle BLOBs in den Speicher geladen; erst wenn diese Grenze erreicht ist, werden alternative Mechanismen (wie temporäre Dateien) eingesetzt. Das Halten von BLOBs im Speicher maximiert die Leistung, kann jedoch zu hohem Speicherverbrauch führen. Verwenden Sie diese Eigenschaft, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen.

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value)=0
```

## Anmerkungen

Dieser Wert wird ignoriert, wenn [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) auf false gesetzt ist, da der Speicher dann der einzige verfügbare Speicherort ist und das Begrenzen der in-Memory-BLOB-Nutzung keine Wirkung hat.

Der Standardwert beträgt 629,145,600 Bytes (600 MB).

Sie können diese Eigenschaft auf null setzen, jedoch wird dennoch ein kleiner Mindestbetrag an Speicher reserviert.

## Siehe auch

* Klasse [IBlobManagementOptions](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)