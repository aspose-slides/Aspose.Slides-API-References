---
title: LinkEmbedDecision
second_title: Riferimento API Java per Aspose.Slides per Android
description: Determina come l'oggetto verrà elaborato durante il salvataggio.
type: docs
url: /it/com.aspose.slides/linkembeddecision/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Determina come l'oggetto verrà elaborato durante il salvataggio.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Link](#Link) | L'oggetto sarà memorizzato esternamente, riferito tramite URL |
| [Embed](#Embed) | L'oggetto dovrebbe essere incorporato in un file generato, se possibile. |
| [Ignore](#Ignore) | L'oggetto verrà ignorato. |
### Collegamento {#Link}
```
public static final int Link
```

L'oggetto sarà memorizzato esternamente, riferito tramite URL

### Incorporamento {#Embed}
```
public static final int Embed
```

L'oggetto dovrebbe essere incorporato in un file generato, se possibile. Se l'incorporamento è impossibile, GetUrl verrà chiamato e, a seconda del risultato, l'oggetto sarà riferito tramite URL o ignorato.

### Ignora {#Ignore}
```
public static final int Ignore
```

L'oggetto verrà ignorato.