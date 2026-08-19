---
title: LinkEmbedDecision
second_title: Aspose.Slides för Java API-referens
description: Bestämmer hur objektet kommer att bearbetas vid sparande.
type: docs
url: /sv/com.aspose.slides/linkembeddecision/
---
**Arv:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Bestämmer hur objektet kommer att bearbetas vid sparande.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Link](#Link) | Objektet kommer att lagras externt, refererat via URL |
| [Embed](#Embed) | Objektet bör bäddas in i en genererad fil om möjligt. |
| [Ignore](#Ignore) | Objektet kommer att ignoreras. |
### Länk {#Link}
```
public static final int Link
```


Objektet kommer att lagras externt, refererat via URL

### Inbäddning {#Embed}
```
public static final int Embed
```


Objektet bör bäddas in i en genererad fil om möjligt. Om inbäddning är omöjlig, GetUrl kommer att anropas och, beroende på resultatet, kommer objektet att refereras via URL eller ignoreras.

### Ignorera {#Ignore}
```
public static final int Ignore
```


Objektet kommer att ignoreras.