---
title: HandleRepeatedSpaces
second_title: Aspose.Slides för Java API-referens
description: Anger hur upprepade vanliga mellanslagstecken ska hanteras vid Markdown-export.
type: docs
url: /sv/com.aspose.slides/handlerepeatedspaces/
---
**Arv:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Anger hur upprepade vanliga mellanslagstecken ska hanteras vid Markdown-export.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [None](#None) | Alla mellanslag bevaras som vanliga mellanslagstecken utan några förändringar. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Omvandlar sekvenser av två eller fler på varandra följande vanliga mellanslag genom att växla mellan vanliga mellanslagstecken och icke-brytande mellanslagentiteter NBSP. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Omvandlar sekvenser av två eller fler på varandra följande vanliga mellanslag genom att bevara det första mellanslaget som ett vanligt mellanslagstecken och ersätta alla efterföljande mellanslag med icke-brytande mellanslagentiteter NBSP. |
### None {#None}
```
public static final int None
```


Alla mellanslag bevaras som vanliga mellanslagstecken utan några förändringar. Ingen transformation tillämpas, och flera på varandra följande mellanslag exporteras som de är.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```


Omvandlar sekvenser av två eller fler på varandra följande vanliga mellanslag genom att växla mellan vanliga mellanslagstecken och icke-brytande mellanslagentiteter NBSP. Det första mellanslaget bevaras alltid som ett vanligt mellanslag.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```


Omvandlar sekvenser av två eller fler på varandra följande vanliga mellanslag genom att bevara det första mellanslaget som ett vanligt mellanslagstecken och ersätta alla efterföljande mellanslag med icke-brytande mellanslagentiteter NBSP.