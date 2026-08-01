---
title: Open()
second_title: Aspose.Slides voor C++ API-referentie
description: Opent het bestand dat wordt weergegeven door het huidige object in de opgegeven modus voor lezen en schrijven en zonder delen.
type: docs
weight: 183
url: /nl/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) methode

Opent het bestand dat wordt weergegeven door het huidige object in de opgegeven modus voor lezen en schrijven en zonder delen.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Specificeert de modus waarin het bestand moet worden geopend |

### Retourwaarde

Een [FileStream](../../filestream/) object dat gekoppeld is aan het bestand dat wordt weergegeven door het huidige object

## FileInfo::Open(FileMode, FileAccess) methode

Opent het bestand dat wordt weergegeven door het huidige object in de opgegeven modus, met het opgegeven toegangstype en zonder delen.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Specificeert de modus waarin het bestand moet worden geopend |
| access | [FileAccess](../../fileaccess/) | Het aangevraagde toegangstype |

### Retourwaarde

Een [FileStream](../../filestream/) object dat gekoppeld is aan het bestand dat wordt weergegeven door het huidige object

## FileInfo::Open(FileMode, FileAccess, FileShare) methode

Opent het bestand dat wordt weergegeven door het huidige object in de opgegeven modus, met het opgegeven toegangstype en deeloptie.

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | Specificeert de modus waarin het bestand moet worden geopend |
| access | [FileAccess](../../fileaccess/) | Het aangevraagde toegangstype |
| share | [FileShare](../../fileshare/) | Het type toegang dat andere [FileStream](../../filestream/) objecten hebben tot het geopende bestand |

### Retourwaarde

Een [FileStream](../../filestream/) object dat gekoppeld is aan het bestand dat wordt weergegeven door het huidige object

## Zie ook

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Klasse [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)