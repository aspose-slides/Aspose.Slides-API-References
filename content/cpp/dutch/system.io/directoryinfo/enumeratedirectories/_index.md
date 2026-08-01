---
title: EnumerateDirectories()
second_title: Aspose.Slides voor C++ API Referentie
description: Retourneert een enumerabele collectie die alle mappen bevat die zich bevinden in de map die door het huidige object wordt vertegenwoordigd.
type: docs
weight: 105
url: /nl/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() methode


Retourneert een enumerabele collectie die alle mappen bevat die zich bevinden in de map die door het huidige object wordt vertegenwoordigd.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) methode


Zoekt naar de mappen die voldoen aan de opgegeven zoekcriteria in de map die door het huidige object wordt vertegenwoordigd.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```


### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Het naampatroon van de te zoeken mappen |

### Retourwaarde

De enumerabele collectie van gedeelde pointers naar [DirectoryInfo](../) objecten die de gevonden mappen vertegenwoordigen waarvan de namen overeenkomen met **searchPattern**

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) methode


Zoekt naar de mappen die voldoen aan de opgegeven zoekcriteria, ofwel in de map die door het huidige object wordt vertegenwoordigd, of in de volledige mappenboom die is geworteld in de map die door het huidige object wordt vertegenwoordigd.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```


### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Het naampatroon van de te zoeken mappen |
| searchOption | [SearchOption](../../searchoption/) | Specificeert of de zoekopdracht alleen in de map die door het huidige object wordt vertegenwoordigd moet worden uitgevoerd, of in de volledige mappenboom die is geworteld in de map die door het huidige object wordt vertegenwoordigd |

### Retourwaarde

De enumerabele collectie van gedeelde pointers naar [DirectoryInfo](../) objecten die de gevonden mappen vertegenwoordigen waarvan de namen overeenkomen met **searchPattern**

## Zie ook

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)