---
title: GetFileSystemEntries()
second_title: Aspose.Slides för C++ API-referens
description: Söker efter filer och kataloger som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet som har den angivna katalogen som rot.
type: docs
weight: 92
url: /sv/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String\&, const String\&, SearchOption) metod


Söker efter filer och kataloger som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet som har den angivna katalogen som rot.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Fullständig eller relativ sökväg till katalogen att söka i |
| searchPattern | const [String](../../../system/string/)\& | Namnmönstret för filer och kataloger att söka efter |
| searchOption | [SearchOption](../../searchoption/) | Anger om sökningen ska utföras endast i den angivna katalogen eller i hela katalogträdet som har den angivna katalogen som rot |

### Returvärde

En array av fullständiga sökvägar till de hittade filerna och katalogerna vars namn matchar **searchPattern**

## Se även

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)