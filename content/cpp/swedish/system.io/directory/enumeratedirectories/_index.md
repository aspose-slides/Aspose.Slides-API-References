---
title: EnumerateDirectories()
second_title: Aspose.Slides för C++ API-referens
description: Söker efter katalogerna som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet som har den angivna katalogen som rot.
type: docs
weight: 27
url: /sv/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String\&, const String\&, SearchOption) metod


Söker efter katalogerna som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet som har den angivna katalogen som rot.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Fullständig eller relativ sökväg till katalogen att söka i |
| searchPattern | const [String](../../../system/string/)\& | Namnmönstret för katalogerna att söka efter |
| searchOption | [SearchOption](../../searchoption/) | Anger om sökningen bara ska utföras i den angivna katalogen eller i hela katalogträdet som har den angivna katalogen som rot |

### Returvärde

Den enumererbara samlingen av fullständiga sökvägar för de hittade katalogerna vars namn matchar **searchPattern**

## Se även

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)