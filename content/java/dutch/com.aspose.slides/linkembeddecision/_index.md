---
title: LinkEmbedDecision
second_title: Aspose.Slides voor Java API Referentie
description: Bepaalt hoe het object wordt verwerkt tijdens het opslaan.
type: docs
url: /nl/com.aspose.slides/linkembeddecision/
---
**Erfenis:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Bepaalt hoe het object wordt verwerkt tijdens het opslaan.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Link](#Link) | Object wordt extern opgeslagen, verwezen via URL |
| [Embed](#Embed) | Object moet worden ingebed in een gegenereerd bestand indien mogelijk. |
| [Ignore](#Ignore) | Object wordt genegeerd. |
### Link {#Link}
```
public static final int Link
```


Object wordt extern opgeslagen, verwezen via URL

### Embed {#Embed}
```
public static final int Embed
```


Object moet worden ingebed in een gegenereerd bestand indien mogelijk. Als inbedden niet mogelijk is, wordt GetUrl aangeroepen en, afhankelijk van het resultaat, wordt het object verwezen via URL of genegeerd.

### Ignore {#Ignore}
```
public static final int Ignore
```


Object wordt genegeerd.