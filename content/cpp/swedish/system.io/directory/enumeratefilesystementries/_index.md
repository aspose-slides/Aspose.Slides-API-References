---
title: EnumerateFileSystemEntries()
second_title: Aspose.Slides för C++ API-referens
description: Söker efter filer och kataloger som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet som har den angivna katalogen som rot.
type: docs
weight: 53
url: /sv/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries(const String\&, const String\&, SearchOption) metod


Söker efter filer och kataloger som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet som har den angivna katalogen som rot.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Fullständig eller relativ sökväg till katalogen att söka i |
| searchPattern | const [String](../../../system/string/)\& | Namnmönster för filerna och katalogerna att söka efter |
| searchOption | [SearchOption](../../searchoption/) | Anger om sökningen ska utföras enbart i den angivna katalogen eller i hela katalogträdet som har den angivna katalogen som rot |

### Returvärde

Den enumererbara samlingen av fullständiga sökvägar till de hittade filerna och katalogerna vars namn matchar **searchPattern**

## Se även

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Klass [String](../../../system/string/)
* Klass [Directory](../)
* Namnrymd [System::IO](../../)
* Library [Aspose.Slides](../../../)