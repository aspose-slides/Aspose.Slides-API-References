---
title: LinkEmbedDecision
second_title: Aspose.Slides para Android mediante la Referencia de API Java
description: Determina cómo se procesará el objeto durante el guardado.
type: docs
url: /es/com.aspose.slides/linkembeddecision/
---
**Herencia:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Determina cómo se procesará el objeto durante el guardado.
## Campos

| Campo | Descripción |
| --- | --- |
| [Link](#Link) | El objeto se almacenará externamente, referenciado por URL |
| [Embed](#Embed) | El objeto debe incorporarse al archivo generado si es posible. |
| [Ignore](#Ignore) | El objeto será ignorado. |
### Link {#Link}
```
public static final int Link
```

El objeto se almacenará externamente, referenciado por URL

### Embed {#Embed}
```
public static final int Embed
```

El objeto debe incorporarse al archivo generado si es posible. Si la incorporación es imposible, se llamará a GetUrl y, según el resultado, el objeto será referenciado por URL o será ignorado.

### Ignore {#Ignore}
```
public static final int Ignore
```

El objeto será ignorado.