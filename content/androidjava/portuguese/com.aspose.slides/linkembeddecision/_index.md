---
title: LinkEmbedDecision
second_title: Aspose.Slides para Android via Referência da API Java
description: Determina como o objeto será processado durante a gravação.
type: docs
url: /pt/com.aspose.slides/linkembeddecision/
---
**Herança:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Determina como o objeto será processado durante a gravação.
## Campos

| Campo | Descrição |
| --- | --- |
| [Link](#Link) | O objeto será armazenado externamente, referenciado por URL |
| [Embed](#Embed) | O objeto deve ser incorporado a um arquivo gerado, se possível. |
| [Ignore](#Ignore) | O objeto será ignorado. |
### Link {#Link}
```
public static final int Link
```


O objeto será armazenado externamente, referenciado por URL

### Embed {#Embed}
```
public static final int Embed
```


O objeto deve ser incorporado a um arquivo gerado, se possível. Se a incorporação for impossível, GetUrl será chamado e, dependendo do resultado, o objeto será referenciado por URL ou ignorado.

### Ignore {#Ignore}
```
public static final int Ignore
```


O objeto será ignorado.