---
title: HandleRepeatedSpaces
second_title: Aspose.Slides pro Android přes Java API Reference
description: Určuje, jak mají být při exportu do Markdownu zpracovány opakované běžné znaky mezery.
type: docs
url: /cs/com.aspose.slides/handlerepeatedspaces/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Specifikuje, jak mají být při exportu do Markdownu zpracovány opakované běžné znaky mezery.

## Pole

| Pole | Popis |
| --- | --- |
| [None](#None) | Všechny mezery jsou zachovány jako běžné znaky mezery bez jakýchkoli změn. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Převádí sekvence dvou nebo více po sobě jdoucích běžných mezer střídáním mezi běžnými znaky mezery a entitami nezlomitelné mezery NBSP. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Převádí sekvence dvou nebo více po sobě jdoucích běžných mezer tak, že zachová první mezeru jako běžný znak mezery a všechny následující mezery nahradí entitami nezlomitelné mezery NBSP. |

### None {#None}
```
public static final int None
```

Všechny mezery jsou zachovány jako běžné znaky mezery bez jakýchkoli změn. Transformace se nepoužije a více po sobě jdoucí mezery jsou exportovány tak, jak jsou.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

Převádí sekvence dvou nebo více po sobě jdoucích běžných mezer střídáním mezi běžnými znaky mezery a entitami nezlomitelné mezery NBSP. První mezera je vždy zachována jako běžná mezera.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

Převádí sekvence dvou nebo více po sobě jdoucích běžných mezer tak, že zachová první mezeru jako běžný znak mezery a všechny následující mezery nahradí entitami nezlomitelné mezery NBSP.