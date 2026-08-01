---
title: HandleRepeatedSpaces
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert hoe herhaalde gewone spatie-tekens moeten worden behandeld tijdens het exporteren naar Markdown.
type: docs
weight: 937
url: /nl/aspose.slides.export/handlerepeatedspaces/
---
## HandleRepeatedSpaces enum

Specificeert hoe herhaalde gewone spatie-tekens moeten worden behandeld tijdens het exporteren naar Markdown.

```cpp
enum class HandleRepeatedSpaces
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | 0 | Alle spaties worden bewaard als gewone spatie-tekens zonder wijzigingen. Er wordt geen transformatie toegepast en meerdere opeenvolgende spaties worden geëxporteerd zoals ze zijn. |
| AlternateSpacesToNbsp | 1 | Zet reeksen van twee of meer opeenvolgende gewone spaties om door te wisselen tussen gewone spatie-tekens en non-breaking-space-entiteiten (**&nbsp;**). De eerste spatie wordt altijd bewaard als een gewone spatie. |
| MultipleSpacesToNbsp | 2 | Zet reeksen van twee of meer opeenvolgende gewone spaties om door de eerste spatie te behouden als een gewoon spatie-teken en alle daaropvolgende spaties te vervangen door non-breaking-space-entiteiten (**&nbsp;**). |

## Zie ook

* Naamruimte [Aspose::Slides::Export](../)
* Bibliotheek [Aspose.Slides](../../)