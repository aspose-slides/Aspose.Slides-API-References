---
title: EnumerateDirectories()
second_title: Aspose.Slides voor C++ API-referentie
description: Zoekt naar de mappen die voldoen aan de opgegeven zoekcriteria, hetzij in de opgegeven map, hetzij in de volledige mapboom met die map als root.
type: docs
weight: 27
url: /nl/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String\&, const String\&, SearchOption) methode


Zoekt naar de mappen die voldoen aan de opgegeven zoekcriteria, hetzij in de opgegeven map, hetzij in de volledige mapboom met die map als root.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Volledig of relatief pad naar de map waarin gezocht moet worden |
| searchPattern | const [String](../../../system/string/)\& | Het naampatroon van de te zoeken mappen |
| searchOption | [SearchOption](../../searchoption/) | Specificeert of de zoekopdracht alleen in de opgegeven map moet worden uitgevoerd of in de volledige mapboom met als root de opgegeven map |

### Retourwaarde

De doorzoekbare collectie van volledige paden van de gevonden mappen waarvan de namen overeenkomen met **searchPattern**

## Zie ook

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)