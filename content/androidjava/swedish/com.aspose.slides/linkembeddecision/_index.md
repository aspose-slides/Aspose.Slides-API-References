---
title: LinkEmbedDecision
second_title: Aspose.Slides för Android via Java API Referens
description: Bestämmer hur objektet kommer att behandlas vid sparning.
type: docs
url: /sv/com.aspose.slides/linkembeddecision/
---
**Arv:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Bestämmer hur objektet kommer att behandlas vid sparning.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Link](#Link) | Objektet kommer att lagras externt, refererat via URL |
| [Embed](#Embed) | Objektet bör bäddas in i en genererad fil om möjligt. |
| [Ignore](#Ignore) | Objektet kommer att ignoreras. |
### Link {#Link}
```
public static final int Link
```


Objektet kommer att lagras externt, refererat via URL

### Embed {#Embed}
```
public static final int Embed
```


Objektet bör bäddas in i en genererad fil om möjligt. Om inbäddning är omöjligt, kommer GetUrl att anropas och, beroende på resultatet, kommer objektet att refereras via URL eller ignoreras.

### Ignore {#Ignore}
```
public static final int Ignore
```


Objektet kommer att ignoreras.