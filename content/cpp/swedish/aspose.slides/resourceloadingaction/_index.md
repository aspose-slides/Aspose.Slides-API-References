---
title: ResourceLoadingAction
second_title: Aspose.Slides för C++ API-referens
description: Anger läget för laddning av externa resurser.
type: docs
weight: 6761
url: /sv/aspose.slides/resourceloadingaction/
---
## ResourceLoadingAction enum


Anger läget för laddning av externa resurser.

```cpp
enum class ResourceLoadingAction
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Default | 0 | [Aspose.Slides](../) kommer att ladda extern resurs som vanligt. |
| Skip | 1 | [Aspose.Slides](../) kommer att hoppa över laddning av extern resurs. Endast länken utan data kommer att lagras för en bild. |
| UserProvided | 2 | [Aspose.Slides](../) kommer att använda byte-array som tillhandahålls av användaren i [IResourceLoadingArgs::SetData](../iresourceloadingargs/setdata/) som bilddata. |

## Se även

* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)