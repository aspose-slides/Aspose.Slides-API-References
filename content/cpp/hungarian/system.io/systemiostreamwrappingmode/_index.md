---
title: SystemIOStreamWrappingMode
second_title: Aspose.Slides for C++ API referencia
description: "Megadja azt a módot, ahogyan a csomagoló rétegek az I/O műveletek során a System::IO::Stream-szerű adatfolyamokon működnek."
type: docs
weight: 599
url: /hu/system.io/systemiostreamwrappingmode/
---
## SystemIOStreamWrappingMode enum

Megadja azt a módot, ahogyan az I/O műveletek során a csomagoló rétegek a [System::IO::Stream](../stream/)-szerű adatfolyamokon működnek.

```cpp
enum class SystemIOStreamWrappingMode
```

### Values

| Név | Érték | Leírás |
| --- | --- | --- |
| Binary | 0 | Egy olyan mód, amely lehetővé teszi a bemeneti műveletek számára, hogy a adatfolyam bájtjait char_type adatokká kódolják, illetve a char_type adatokat adatfolyam bájtokká dekódolják a kimeneti műveletekhez. |
| Conversion | 1 | Egy olyan mód, amely lehetővé teszi a bemeneti műveletek számára, hogy az adatfolyam bájtjait **uint8_t** típusból char_type típusba konvertálják, és a kimeneti műveletek esetén visszafelé. |

## Lásd még

* Névtér [System::IO](../)
* Könyvtár [Aspose.Slides](../../)