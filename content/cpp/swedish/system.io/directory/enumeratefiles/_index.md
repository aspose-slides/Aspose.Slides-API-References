---
title: EnumerateFiles()
second_title: Aspose.Slides för C++ API-referens
description: Söker efter de filer som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet som är rotat i den angivna katalogen.
type: docs
weight: 40
url: /sv/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String\&, const String\&, SearchOption) metod


Söker efter de filer som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet som är rotat i den angivna katalogen.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Fullständig eller relativ sökväg till katalogen att söka i |
| searchPattern | const [String](../../../system/string/)\& | Namnmönstret för filerna att söka efter |
| searchOption | [SearchOption](../../searchoption/) | Anger om sökningen ska utföras endast i den angivna katalogen eller i hela katalogträdet som är rotat i den angivna katalogen |

### Returvärde

Den uppräkningsbara samlingen av fullständiga sökvägar för de hittade filerna vars namn matchar **searchPattern**

## Se även

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)