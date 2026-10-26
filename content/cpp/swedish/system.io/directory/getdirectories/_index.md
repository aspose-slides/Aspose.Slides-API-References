---
title: GetDirectories()
second_title: Aspose.Slides för C++ API-referens
description: Söker efter de kataloger som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet som har den angivna katalogen som rot.
type: docs
weight: 66
url: /sv/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String\&, const String\&, SearchOption) metod


Söker efter de kataloger som uppfyller de angivna sökkriterierna antingen i den angivna katalogen eller i hela katalogträdet som har den angivna katalogen som rot.

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Fullständig eller relativ sökväg till katalogen att söka i |
| searchPattern | const [String](../../../system/string/)\& | Namnmönstret för katalogerna att söka efter |
| searchOption | [SearchOption](../../searchoption/) | Anger om sökningen ska utföras endast i den angivna katalogen eller i hela katalogträdet som har den angivna katalogen som rot |

### Returvärde

En array av fullständiga sökvägar för de hittade katalogerna vars namn matchar **searchPattern**

## Se även

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [String](../../../system/string/)
* Klass [Directory](../)
* Namnrymd [System::IO](../../)
* Library [Aspose.Slides](../../../)