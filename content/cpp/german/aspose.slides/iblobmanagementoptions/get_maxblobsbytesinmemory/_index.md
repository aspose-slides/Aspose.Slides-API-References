---
title: get_MaxBlobsBytesInMemory()
second_title: Aspose.Slides für C++ API-Referenz
description: Definiert die maximale Gesamtsumme (in Bytes), die alle BLOBs im Speicher belegen können. Standardmäßig werden alle BLOBs in den Speicher geladen; erst wenn dieses Limit erreicht ist, werden alternative Mechanismen (wie temporäre Dateien) eingesetzt. Das Halten von BLOBs im Speicher maximiert die Leistung, kann jedoch zu hohem Speicherverbrauch führen. Verwenden Sie diese Eigenschaft, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen.
type: docs
weight: 79
url: /de/aspose.slides/iblobmanagementoptions/get_maxblobsbytesinmemory/
---
## IBlobManagementOptions::get_MaxBlobsBytesInMemory() Methode


Definiert die maximale Gesamtsumme (in Bytes), die alle BLOBs im Speicher belegen dürfen. Standardmäßig werden alle BLOBs in den Speicher geladen; erst wenn dieses Limit erreicht ist, werden alternative Mechanismen (wie temporäre Dateien) verwendet. Das Halten von BLOBs im Speicher maximiert die Leistung, kann jedoch zu hohem Speicherverbrauch führen. Verwenden Sie diese Eigenschaft, um das Verhalten an Ihre Umgebung oder Anforderungen anzupassen.

```cpp
virtual uint64_t Aspose::Slides::IBlobManagementOptions::get_MaxBlobsBytesInMemory()=0
```

## Hinweise


Dieser Wert wird ignoriert, wenn [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) auf false gesetzt ist, da dann der Speicher der einzige verfügbare Speicherort ist und das Begrenzen der im Speicher befindlichen BLOB-Nutzung keine Wirkung hat. 

Der Standardwert ist 629,145,600 Bytes (600 MB). 

Sie können diese Eigenschaft auf null setzen, jedoch wird ein kleiner Mindestwert an Speicher weiterhin reserviert. 
## Siehe auch

* Klasse [IBlobManagementOptions](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)