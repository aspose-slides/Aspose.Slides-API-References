---
title: LinkEmbedDecision
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Určuje, jak bude objekt při ukládání zpracován.
type: docs
url: /cs/com.aspose.slides/linkembeddecision/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Určuje, jak bude objekt při ukládání zpracován.
## Pole

| Pole | Popis |
| --- | --- |
| [Link](#Link) | Objekt bude uložen externě a bude odkazován pomocí URL |
| [Embed](#Embed) | Objekt by měl být vložen do vygenerovaného souboru, pokud je to možné. |
| [Ignore](#Ignore) | Objekt bude ignorován. |
### Odkaz {#Link}
```
public static final int Link
```

Objekt bude uložen externě a bude odkazován pomocí URL

### Vložit {#Embed}
```
public static final int Embed
```

Objekt by měl být vložen do vygenerovaného souboru, pokud je to možné. Pokud vložení není možné, bude zavolána metoda GetUrl a v závislosti na výsledku bude objekt odkazován pomocí URL nebo bude ignorován.

### Ignorovat {#Ignore}
```
public static final int Ignore
```

Objekt bude ignorován.