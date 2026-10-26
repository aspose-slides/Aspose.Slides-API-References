---
title: GetFiles()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een array met gedeelde pointers naar FileInfo-objecten die alle mappen vertegenwoordigen die zich bevinden in de map die wordt gerepresenteerd door het huidige object.
type: docs
weight: 157
url: /nl/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() methode

Retourneert een array met gedeelde pointers naar [FileInfo](../../fileinfo/) objecten die alle mappen vertegenwoordigen die zich bevinden in de map die wordt gerepresenteerd door het huidige object.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) methode

Zoekt naar de bestanden die voldoen aan de opgegeven zoekcriteria in de map die wordt gerepresenteerd door het huidige object.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Het naamspatroon van de te zoeken bestanden |

### Retourwaarde

Een array met gedeelde pointers naar [FileInfo](../../fileinfo/) objecten die de gevonden bestanden vertegenwoordigen waarvan de namen overeenkomen met **searchPattern**

## DirectoryInfo::GetFiles(const String\&, SearchOption) methode

Zoekt naar de bestanden die voldoen aan de opgegeven zoekcriteria, hetzij in de map die wordt gerepresenteerd door het huidige object, hetzij in de volledige mappenboom die is geworteld in de map die wordt gerepresenteerd door het huidige object.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Het naamspatroon van de te zoeken bestanden |
| searchOption | [SearchOption](../../searchoption/) | Geeft aan of de zoekopdracht alleen in de map die wordt gerepresenteerd door het huidige object moet worden uitgevoerd of in de volledige mappenboom die is geworteld in die map |

### Retourwaarde

Een array met gedeelde pointers naar [FileInfo](../../fileinfo/) objecten die de gevonden bestanden vertegenwoordigen waarvan de namen overeenkomen met **searchPattern**

## Zie ook

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)