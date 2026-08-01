---
title: GetDirectories()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een array met gedeelde pointers naar DirectoryInfo-objecten die alle mappen vertegenwoordigen die zich bevinden in de map die wordt vertegenwoordigd door het huidige object.
type: docs
weight: 144
url: /nl/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() methode


Retourneert een array met gedeelde pointers naar [DirectoryInfo](../) objecten die alle mappen vertegenwoordigen die zich bevinden in de map die wordt vertegenwoordigd door het huidige object.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) methode


Zoekt naar de mappen die voldoen aan de opgegeven zoekcriteria in de map die wordt vertegenwoordigd door het huidige object.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Het naampatroon van de te zoeken mappen |

### Retourwaarde

Een array met gedeelde pointers naar [DirectoryInfo](../) objecten die de gevonden mappen vertegenwoordigen waarvan de namen overeenkomen met **searchPattern**

## DirectoryInfo::GetDirectories(const String\&, SearchOption) methode


Zoekt naar de mappen die voldoen aan de opgegeven zoekcriteria, ofwel in de map die wordt vertegenwoordigd door het huidige object, of in de volledige boomstructuur waarvan de wortel de map is die wordt vertegenwoordigd door het huidige object.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Het naampatroon van de te zoeken mappen |
| searchOption | [SearchOption](../../searchoption/) | Geeft aan of de zoekopdracht alleen moet worden uitgevoerd in de map die wordt vertegenwoordigd door het huidige object, of in de volledige boomstructuur waarvan de wortel de map is die wordt vertegenwoordigd door het huidige object |

### Retourwaarde

Een array met gedeelde pointers naar [DirectoryInfo](../) objecten die de gevonden mappen vertegenwoordigen waarvan de namen overeenkomen met **searchPattern**

## Zie ook

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Klasse [DirectoryInfo](../)
* Klasse [String](../../../system/string/)
* Naamruimte [System::IO](../../)
* Library [Aspose.Slides](../../../)