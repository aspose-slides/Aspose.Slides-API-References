---
title: GetFileSystemEntries()
second_title: Aspose.Slides voor C++ API-referentie
description: Zoekt naar de bestanden en mappen die voldoen aan de opgegeven zoekcriteria, hetzij in de opgegeven map, hetzij in de volledige mappenboom die in de opgegeven map is geworteld.
type: docs
weight: 92
url: /nl/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String\&, const String\&, SearchOption) method


Zoekt naar de bestanden en mappen die voldoen aan de opgegeven zoekcriteria, hetzij in de opgegeven map, hetzij in de volledige mappenboom die in de opgegeven map is geworteld.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Volledig of relatief pad naar de map waarin gezocht moet worden |
| searchPattern | const [String](../../../system/string/)\& | Het naampatroon van de bestanden en mappen waarnaar gezocht wordt |
| searchOption | [SearchOption](../../searchoption/) | Geeft aan of de zoekopdracht alleen in de opgegeven map moet worden uitgevoerd of in de volledige mappenboom die in de opgegeven map is geworteld |

### Retourwaarde

Een array met volledige paden van de gevonden bestanden en mappen waarvan de namen overeenkomen met **searchPattern**

## Zie ook

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)