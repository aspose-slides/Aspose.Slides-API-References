---
title: EnumerateFileSystemEntries()
second_title: Aspose.Slides voor C++ API-referentie
description: Zoekt naar de bestanden en mappen die voldoen aan de opgegeven zoekcriteria, hetzij in de opgegeven map, hetzij in de volledige mapboom die is geworteld in de opgegeven map.
type: docs
weight: 53
url: /nl/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries(const String\&, const String\&, SearchOption) methode

Zoekt naar de bestanden en mappen die voldoen aan de opgegeven zoekcriteria, hetzij in de opgegeven map, hetzij in de volledige mapboom die is geworteld in de opgegeven map.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Volledig of relatief pad naar de map waarin gezocht moet worden |
| searchPattern | const [String](../../../system/string/)\& | Het naampatroon van de bestanden en mappen waarnaar gezocht wordt |
| searchOption | [SearchOption](../../searchoption/) | Geeft aan of de zoekactie alleen in de opgegeven map moet worden uitgevoerd of in de volledige mapboom die is geworteld in de opgegeven map |

### Retourwaarde

De doorzoekbare collectie van volledige paden van de gevonden bestanden en mappen waarvan de namen overeenkomen met **searchPattern**

## Zie ook

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)