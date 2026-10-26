---
title: GetFileSystemInfos()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een array met gedeelde pointers naar FileSystemInfo objecten die alle bestanden en mappen vertegenwoordigen die zich bevinden in de map die door het huidige object wordt gerepresenteerd.
type: docs
weight: 170
url: /nl/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() methode


Retourneert een array met gedeelde pointers naar [FileSystemInfo](../../filesysteminfo/) objecten die alle bestanden en mappen vertegenwoordigen die zich in de map bevinden die door het huidige object wordt gerepresenteerd.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) methode


Zoekt naar de bestanden en mappen die voldoen aan de opgegeven zoekcriteria in de map die door het huidige object wordt gerepresenteerd.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Het naam patroon van de bestanden en mappen waarnaar gezocht moet worden |

### Retourwaarde

Een array met gedeelde pointers naar [FileSystemInfo](../../filesysteminfo/) objecten die de gevonden bestanden en mappen vertegenwoordigen waarvan de namen overeenkomen met **searchPattern**

## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) methode


Zoekt naar de bestanden en mappen die voldoen aan de opgegeven zoekcriteria ofwel in de map die door het huidige object wordt gerepresenteerd of in de gehele mapboom die is geworteld in de map die door het huidige object wordt gerepresenteerd.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Het naam patroon van de bestanden en mappen waarnaar gezocht moet worden |
| searchOption | [SearchOption](../../searchoption/) | Geeft aan of de zoekopdracht alleen in de map die door het huidige object wordt gerepresenteerd moet worden uitgevoerd of in de volledige mapboom die is geworteld in de map die door het huidige object wordt gerepresenteerd |

### Retourwaarde

Een array met gedeelde pointers naar [FileSystemInfo](../../filesysteminfo/) objecten die de gevonden bestanden en mappen vertegenwoordigen waarvan de namen overeenkomen met **searchPattern**

## Zie ook

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Klasse [DirectoryInfo](../)
* Klasse [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)