---
title: HandleRepeatedSpaces
second_title: Aspose.Slides voor Java API-referentie
description: Specificeert hoe herhaalde gewone spatiekarakters moeten worden verwerkt tijdens de Markdown-export.
type: docs
url: /nl/com.aspose.slides/handlerepeatedspaces/
---
**Erfenis:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Specificeert hoe herhaalde gewone spatiekarakters moeten worden verwerkt tijdens de Markdown-export.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [None](#None) | Alle spaties worden bewaard als gewone spatiekarakters zonder wijzigingen. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Converteert reeksen van twee of meer opeenvolgende gewone spaties door te wisselen tussen gewone spatiekarakters en niet-brekende spatie-entiteiten NBSP. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Converteert reeksen van twee of meer opeenvolgende gewone spaties door de eerste spatie te behouden als een gewoon spatiekarakter en alle volgende spaties te vervangen door niet-brekende spatie-entiteiten NBSP. |
### None {#None}
```
public static final int None
```

Alle spaties worden bewaard als gewone spatiekarakters zonder wijzigingen. Er wordt geen transformatie toegepast en meerdere opeenvolgende spaties worden onveranderd geëxporteerd.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

Converteert reeksen van twee of meer opeenvolgende gewone spaties door te wisselen tussen gewone spatiekarakters en niet-brekende spatie-entiteiten NBSP. De eerste spatie wordt altijd bewaard als een gewone spatie.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

Converteert reeksen van twee of meer opeenvolgende gewone spaties door de eerste spatie te behouden als een gewoon spatiekarakter en alle volgende spaties te vervangen door niet-brekende spatie-entiteiten NBSP.