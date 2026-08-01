---
title: EnumerateFiles()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een enumerabele collectie die alle bestanden bevat die zich in de map bevinden die door het huidige object wordt vertegenwoordigd.
type: docs
weight: 118
url: /nl/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() methode

Retourneert een enumerabele collectie die alle bestanden bevat die zich in de map bevinden die door het huidige object wordt vertegenwoordigd.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) methode

Zoekt naar de bestanden die voldoen aan de opgegeven zoekcriteria in de map die door het huidige object wordt vertegenwoordigd.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Het naampatroon van de te zoeken bestanden |

### Retourwaarde

De enumerabele collectie van shared pointers naar [FileInfo](../../fileinfo/) objecten die de gevonden bestanden vertegenwoordigen waarvan de namen overeenkomen met **searchPattern**

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) methode

Zoekt naar de bestanden die voldoen aan de opgegeven zoekcriteria, hetzij in de map die door het huidige object wordt vertegenwoordigd, hetzij in de volledige mappenboom die in die map is geworteld.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Het naampatroon van de te zoeken bestanden |
| searchOption | [SearchOption](../../searchoption/) | Specificeert of de zoekopdracht alleen in de map die door het huidige object wordt vertegenwoordigd moet worden uitgevoerd of in de gehele mappenboom die in die map is geworteld |

### Retourwaarde

De enumerabele collectie van shared pointers naar [FileInfo](../../fileinfo/) objecten die de gevonden bestanden vertegenwoordigen waarvan de namen overeenkomen met **searchPattern**

## Zie ook

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasse [DirectoryInfo](../)
* Klasse [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)