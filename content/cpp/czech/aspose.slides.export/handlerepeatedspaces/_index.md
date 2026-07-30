---
title: HandleRepeatedSpaces
second_title: Aspose.Slides pro referenci API C++
description: Určuje, jak mají být při exportu do Markdownu zpracovány opakované běžné mezerné znaky.
type: docs
weight: 937
url: /cs/aspose.slides.export/handlerepeatedspaces/
---
## HandleRepeatedSpaces enum

Určuje, jak mají být při exportu do Markdownu zpracovány opakované běžné mezerné znaky.

```cpp
enum class HandleRepeatedSpaces
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| None | 0 | Všechny mezery jsou zachovány jako běžné mezerné znaky bez jakýchkoli změn. Není provedena žádná transformace a více po sobě jdoucích mezer je exportováno tak, jak jsou. |
| AlternateSpacesToNbsp | 1 | Převádí sekvence dvou nebo více po sobě jdoucích běžných mezer tak, že střídavě používá běžné mezerné znaky a neoddělitelné mezery (**&nbsp;**). První mezera je vždy zachována jako běžná mezera. |
| MultipleSpacesToNbsp | 2 | Převádí sekvence dvou nebo více po sobě jdoucích běžných mezer tak, že první mezera je zachována jako běžný mezerný znak a všechny následující mezery jsou nahrazeny neoddělitelnými mezerami (**&nbsp;**). |

## Viz také

* Namespace [Aspose::Slides::Export](../)
* Knihovna [Aspose.Slides](../../)