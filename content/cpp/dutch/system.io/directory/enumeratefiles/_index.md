---
title: EnumerateFiles()
second_title: Aspose.Slides voor C++ API-referentie
description: Zoekt naar de bestanden die voldoen aan de opgegeven zoekcriteria, hetzij in de opgegeven map, hetzij in de volledige boomstructuur die in de opgegeven map is geworteld.
type: docs
weight: 40
url: /nl/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String\&, const String\&, SearchOption) methode


Zoekt naar de bestanden die voldoen aan de opgegeven zoekcriteria, hetzij in de opgegeven map, hetzij in de volledige boomstructuur die in de opgegeven map is geworteld.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Volledig of relatief pad naar de map waarin gezocht moet worden |
| searchPattern | const [String](../../../system/string/)\& | Het naampatroon van de te zoeken bestanden |
| searchOption | [SearchOption](../../searchoption/) | Geeft aan of de zoekopdracht alleen in de opgegeven map moet worden uitgevoerd of in de volledige boomstructuur die in de opgegeven map is geworteld |

### Retourwaarde

De doorzoekbare collectie van volledige paden van de gevonden bestanden waarvan de namen overeenkomen met **searchPattern**

## Zie ook

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Klasse [String](../../../system/string/)
* Klasse [Directory](../)
* Naamruimte [System::IO](../../)
* Library [Aspose.Slides](../../../)