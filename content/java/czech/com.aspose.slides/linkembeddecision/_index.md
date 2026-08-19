---
title: LinkEmbedDecision
second_title: Aspose.Slides pro Java API Reference
description: Určuje, jak bude objekt během ukládání zpracován.
type: docs
url: /cs/com.aspose.slides/linkembeddecision/
---
**Dědičnost:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Určuje, jak bude objekt zpracován během ukládání.
## Pole

| Pole | Popis |
| --- | --- |
| [Link](#Link) | Objekt bude uložen externě, odkazován pomocí URL |
| [Embed](#Embed) | Objekt by měl být vložen do generovaného souboru, pokud je to možné. |
| [Ignore](#Ignore) | Objekt bude ignorován. |
### Odkaz {#Link}
```
public static final int Link
```

Objekt bude uložen externě, odkazován pomocí URL

### Vložit {#Embed}
```
public static final int Embed
```

Objekt by měl být vložen do generovaného souboru, pokud je to možné. Pokud je vložení nemožné, bude zavolána metoda GetUrl a v závislosti na výsledku bude objekt odkazován pomocí URL nebo bude ignorován.

### Ignorovat {#Ignore}
```
public static final int Ignore
```

Objekt bude ignorován.