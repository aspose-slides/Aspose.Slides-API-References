---
title: LinkEmbedDecision
second_title: Riferimento API di Aspose.Slides per Java
description: Determina come l'oggetto verrà elaborato durante il salvataggio.
type: docs
url: /it/com.aspose.slides/linkembeddecision/
---
**Eredità:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Determina come l'oggetto verra elaborato durante il salvataggio.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Link](#Link) | L'oggetto sara memorizzato esternamente, referenziato tramite URL |
| [Embed](#Embed) | L'oggetto dovrebbe essere incorporato in un file generato, se possibile. |
| [Ignore](#Ignore) | L'oggetto sara ignorato. |
### Link {#Link}
```
public static final int Link
```


L'oggetto sara memorizzato esternamente, referenziato tramite URL

### Embed {#Embed}
```
public static final int Embed
```


L'oggetto dovrebbe essere incorporato in un file generato, se possibile. Se l'incorporamento e impossibile, GetUrl sara chiamato e, a seconda del risultato, l'oggetto sara referenziato tramite URL o ignorato.

### Ignore {#Ignore}
```
public static final int Ignore
```


L'oggetto sara ignorato.