---
title: LinkEmbedDecision
second_title: Referencia de la API de Aspose.Slides para C++
description: Determina cómo se procesará el objeto durante el guardado.
type: docs
weight: 911
url: /es/aspose.slides.export/linkembeddecision/
---
## LinkEmbedDecision enumeración

Determina cómo se procesará el objeto durante el guardado.

```cpp
enum class LinkEmbedDecision
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Link | 0 | El objeto se almacenará externamente, referenciado por URL |
| Embed | 1 | El objeto debe integrarse en un archivo generado si es posible. Si la integración es imposible, se llamará a GetUrl y, según el resultado, el objeto será referenciado por URL o ignorado. |
| Ignore | 2 | El objeto será ignorado. |

## Véase también

* Espacio de nombres [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)