---
title: GetDirectories()
second_title: Aspose.Slides voor C++ API-referentie
description: Zoekt naar de mappen die voldoen aan de opgegeven zoekcriteria, hetzij in de opgegeven map, hetzij in de volledige mapstructuur die is geworteld in de opgegeven map.
type: docs
weight: 66
url: /nl/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String\&, const String\&, SearchOption) methode

Zoekt naar de mappen die voldoen aan de opgegeven zoekcriteria, hetzij in de opgegeven map, hetzij in de volledige mapstructuur die is geworteld in de opgegeven map.

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Volledig of relatief pad naar de map waarin gezocht moet worden |
| searchPattern | const [String](../../../system/string/)\& | Het naam patroon van de mappen om te zoeken |
| searchOption | [SearchOption](../../searchoption/) | Geeft aan of de zoekopdracht alleen in de opgegeven map moet worden uitgevoerd of in de volledige mapstructuur die is geworteld in de opgegeven map |

### Retourwaarde

Een array van volledige paden van de gevonden mappen waarvan de namen overeenkomen met **searchPattern**

## Zie ook

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [Directory](../)
* Namespace [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)