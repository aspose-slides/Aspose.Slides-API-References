---
title: EnumerateFileSystemInfos()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een enumeratebare collectie met alle bestanden en mappen die zich bevinden in de map die wordt weergegeven door het huidige object.
type: docs
weight: 131
url: /nl/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() methode


Retourneert een enumeratebare collectie met alle bestanden en mappen die zich bevinden in de map die wordt weergegeven door het huidige object.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) methode


Doorzoekt de bestanden en mappen die voldoen aan de opgegeven zoekcriteria in de map die wordt weergegeven door het huidige object.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Het naampatroon van de bestanden en mappen waarnaar gezocht moet worden |

### Retourwaarde

De enumeratebare collectie van shared pointers naar [FileSystemInfo](../../filesysteminfo/)-objecten die de gevonden bestanden en mappen vertegenwoordigen waarvan de namen overeenkomen met **searchPattern**

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) methode


Doorzoekt de bestanden en mappen die voldoen aan de opgegeven zoekcriteria, hetzij in de map die wordt weergegeven door het huidige object, hetzij in de volledige mapboom die is geworteld in de map die wordt weergegeven door het huidige object.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Het naampatroon van de bestanden en mappen waarnaar gezocht moet worden |
| searchOption | [SearchOption](../../searchoption/) | Bepaalt of de zoekopdracht alleen in de map die wordt weergegeven door het huidige object moet worden uitgevoerd of in de volledige mapboom die is geworteld in de map die wordt weergegeven door het huidige object |

### Retourwaarde

De enumeratebare collectie van shared pointers naar [FileSystemInfo](../../filesysteminfo/)-objecten die de gevonden bestanden en mappen vertegenwoordigen waarvan de namen overeenkomen met **searchPattern**

## Zie ook

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)