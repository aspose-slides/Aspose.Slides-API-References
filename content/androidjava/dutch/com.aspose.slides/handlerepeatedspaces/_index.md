---
title: HandleRepeatedSpaces
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert hoe herhaalde gewone spatie-tekens moeten worden behandeld tijdens Markdown-export.
type: docs
url: /nl/com.aspose.slides/handlerepeatedspaces/
---
**Erfenis:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Specificeert hoe herhaalde gewone spatie-tekens moeten worden behandeld tijdens Markdown-export.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [None](#None) | Alle spaties worden bewaard als gewone spatie-tekens zonder wijzigingen. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Zet reeksen van twee of meer opeenvolgende gewone spaties om door af te wisselen tussen gewone spatie-tekens en non-breaking-space entiteiten NBSP. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Zet reeksen van twee of meer opeenvolgende gewone spaties om door de eerste spatie te behouden als een gewone spatie en alle daaropvolgende spaties te vervangen door non-breaking-space entiteiten NBSP. |
### None {#None}
```
public static final int None
```

Alle spaties worden bewaard als gewone spatie-tekens zonder wijzigingen. Er wordt geen transformatie toegepast, en meerdere opeenvolgende spaties worden geëxporteerd zoals ze zijn.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

Zet reeksen van twee of meer opeenvolgende gewone spaties om door af te wisselen tussen gewone spatie-tekens en non-breaking-space entiteiten NBSP. De eerste spatie wordt altijd bewaard als een gewone spatie.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

Zet reeksen van twee of meer opeenvolgende gewone spaties om door de eerste spatie te behouden als een gewone spatie en alle daaropvolgende spaties te vervangen door non-breaking-space entiteiten NBSP.