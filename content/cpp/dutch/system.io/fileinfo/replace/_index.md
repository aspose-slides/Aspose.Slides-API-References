---
title: Replace()
second_title: Aspose.Slides voor C++ API-referentie
description: Vervangt de inhoud van een opgegeven bestemmingsbestand door het bestand dat wordt vertegenwoordigd door het huidige FileInfo-object en maakt een back-up van het vervangen bestand.
type: docs
weight: 131
url: /nl/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) methode


Vervangt de inhoud van een opgegeven bestemmingsbestand door het bestand dat wordt vertegenwoordigd door het huidige [FileInfo](../)-object en maakt een back-up van het vervangen bestand.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Een naam van het bestand dat moet worden vervangen |
| destinationBackupFileName | const [String](../../../system/string/)\& | Een naam van het back-upbestand |

### Retourwaarde

Een FileInfor-object dat het bestand aangeeft waarnaar **destinationFileName** wijst

## FileInfo::Replace(const String\&, const String\&, bool) methode


Vervangt de inhoud van een opgegeven bestemmingsbestand door het bestand dat wordt vertegenwoordigd door het huidige [FileInfo](../)-object en maakt een back-up van het vervangen bestand.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | Een naam van het bestand dat moet worden vervangen |
| destinationBackupFileName | const [String](../../../system/string/)\& | Een naam van het back-upbestand |
| ignoreMetadataErrors | **bool** | Specificeert of de samenvoegfouten van het vervangen bestand naar het vervangende bestand moeten worden genegeerd (true) of niet (false) |

### Retourwaarde

Een FileInfor-object dat het bestand aangeeft waarnaar **destinationFileName** wijst

## Zie ook

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Klasse [String](../../../system/string/)
* Klasse [FileInfo](../)
* Naamruimte [System::IO](../../)
* Library [Aspose.Slides](../../../)