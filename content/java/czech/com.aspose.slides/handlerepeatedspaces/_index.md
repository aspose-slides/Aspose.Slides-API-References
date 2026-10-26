---
title: HandleRepeatedSpaces
second_title: Aspose.Slides pro Java API Reference
description: Určuje, jak mají být během exportu do Markdownu zpracovány opakované běžné znaky mezery.
type: docs
url: /cs/com.aspose.slides/handlerepeatedspaces/
---
**Dědičnost:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Určuje, jak mají být během exportu do Markdownu zpracovány opakované běžné mezery.
## Pole

| Pole | Popis |
| --- | --- |
| [None](#None) | Všechny mezery jsou zachovány jako běžné mezery bez jakýchkoli změn. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Převádí sekvence dvou nebo více po sobě jdoucích běžných mezer střídáním mezi běžnými mezerami a entity neoddělitelných mezer (NBSP). |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Převádí sekvence dvou nebo více po sobě jdoucích běžných mezer tak, že první mezeru zachová jako běžnou mezeru a všechny následující mezery nahradí entity neoddělitelných mezer (NBSP). |
### None {#None}
```
public static final int None
```


Všechny mezery jsou zachovány jako běžné mezery bez jakýchkoli změn. Žádná transformace se neaplikuje a více po sobě jdoucí mezery jsou exportovány tak, jak jsou.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```


Převádí sekvence dvou nebo více po sobě jdoucích běžných mezer střídáním mezi běžnými mezerami a entity neoddělitelných mezer (NBSP). První mezera je vždy zachována jako běžná mezera.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```


Převádí sekvence dvou nebo více po sobě jdoucích běžných mezer tak, že první mezeru zachová jako běžnou mezeru a všechny následující mezery nahradí entity neoddělitelných mezer (NBSP).