---
title: LinkEmbedDecision
second_title: Referência da API Aspose.Slides para Java
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
| [Link](#Link) | Objeto será armazenado externamente, referenciado por URL |
| [Embed](#Embed) | Objeto deve ser incorporado a um arquivo gerado, se possível. |
| [Ignore](#Ignore) | Objeto será ignorado. |
### Link {#Link}
```
public static final int Link
```


Objeto será armazenado externamente, referenciado por URL

### Incorporar {#Embed}
```
public static final int Embed
```


Objeto deve ser incorporado a um arquivo gerado, se possível. Se a incorporação for impossível, GetUrl será chamado e, dependendo do resultado, o objeto será referenciado por URL ou ignorado.

### Ignorar {#Ignore}
```
public static final int Ignore
```


Objeto será ignorado.