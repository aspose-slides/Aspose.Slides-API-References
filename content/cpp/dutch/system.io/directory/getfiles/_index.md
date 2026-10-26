---
title: GetFiles()
second_title: Aspose.Slides voor C++ API-referentie
description: Zoekt naar de bestanden die voldoen aan de opgegeven zoekcriteria, hetzij in de opgegeven map, hetzij in de volledige mapboom met als wortel de opgegeven map.
type: docs
weight: 79
url: /nl/system.io/directory/getfiles/
---
## Directory::GetFiles(const String\&, const String\&, SearchOption) methode

Zoekt naar de bestanden die voldoen aan de opgegeven zoekcriteria, hetzij in de opgegeven map, hetzij in de volledige mapboom met als wortel de opgegeven map.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Volledig of relatief pad naar de map waarin gezocht moet worden |
| searchPattern | const [String](../../../system/string/)\& | Het naamspatroon van de te zoeken bestanden |
| searchOption | [SearchOption](../../searchoption/) | Geeft aan of de zoekopdracht alleen in de opgegeven map moet worden uitgevoerd of in de volledige mapboom met als wortel de opgegeven map |

### Return Value

Een array van volledige paden van de gevonden bestanden waarvan de namen overeenkomen met **searchPattern**

## See Also

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [Directory](../)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)