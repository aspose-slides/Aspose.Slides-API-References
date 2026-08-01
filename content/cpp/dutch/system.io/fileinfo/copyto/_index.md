---
title: CopyTo()
second_title: Aspose.Slides voor C++ API-referentie
description: Kopieert het bestand dat door het huidige object wordt vertegenwoordigd naar de opgegeven locatie. Als het bestemmingsbestand al bestaat, faalt de kopie.
type: docs
weight: 105
url: /nl/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) methode


Kopieert het bestand dat wordt vertegenwoordigd door het huidige object naar de opgegeven locatie. Als het bestemmingsbestand al bestaat, faalt de kopie.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | De naam van het bestemmingsbestand |

### Retourwaarde

Een [FileInfo](../) object dat de kopie vertegenwoordigt

## FileInfo::CopyTo(const String\&, bool) methode


Kopieert het bestand dat wordt vertegenwoordigd door het huidige object naar de opgegeven locatie. Een parameter geeft aan of een bestaand bestemmingsbestand moet worden overschreven.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | De naam van het bestemmingsbestand |
| overwrite | **bool** | True als het bestaande bestemmingsbestand moet worden overschreven, false als het kopiëren moet mislukken wanneer het bestemmingsbestand al bestaat |

### Retourwaarde

Een [FileInfo](../) object dat de kopie vertegenwoordigt

## Zie ook

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Klasse [String](../../../system/string/)
* Klasse [FileInfo](../)
* Naamruimte [System::IO](../../)
* Library [Aspose.Slides](../../../)