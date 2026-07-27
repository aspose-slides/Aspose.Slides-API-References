---
title: EmbeddingLevel
second_title: Referencia de API de Aspose.Slides para C++
description: Representa los derechos de licencia para incrustar la fuente.
type: docs
weight: 5786
url: /es/aspose.slides/embeddinglevel/
---
## EmbeddingLevel enum

Representa los derechos de licencia para incrustar la fuente.

```cpp
enum class EmbeddingLevel : uint16_t
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Installable | 0 | [Fonts](../fonts/) con esta configuración indica que pueden incrustarse e instalarse permanentemente en el sistema remoto por una aplicación. El usuario del sistema remoto adquiere los mismos derechos, obligaciones y licencias para esa fuente que el comprador original de la fuente, y está sujeto al mismo acuerdo de licencia de usuario final, derechos de autor, patente de diseño y/o marca registrada que tenía el comprador original. |
| Restricted | 2 | [Fonts](../fonts/) que solo tienen este bit activado no deben modificarse, incrustarse o intercambiarse de ninguna manera sin obtener primero el permiso del propietario legal. |
| PreviewPrint | 4 | Cuando este bit está activado, la fuente puede incrustarse y cargarse temporalmente en el sistema remoto. Los documentos que contienen fuentes Preview & Print deben abrirse \"read-only;\" no se pueden aplicar ediciones al documento. |
| Editable | 8 | Cuando este bit está activado, la fuente puede incrustarse pero solo debe instalarse temporalmente en otros sistemas. A diferencia de las fuentes Preview & Print, los documentos que contienen fuentes Editable pueden abrirse para lectura, se permite la edición y los cambios pueden guardarse. |
| NoSubsetting | 256 | Cuando este bit está activado, la fuente no puede ser subestablecida antes de incrustarse. Otras restricciones de incrustación especificadas en los bits 0-3 y 9 también se aplican. |
| BitmapOnly | 512 | Cuando este bit está activado, solo los mapas de bits contenidos en la fuente pueden incrustarse. No se pueden incrustar datos de contorno. Si no hay mapas de bits disponibles en la fuente, entonces la fuente se considera no incrustable y los servicios de incrustación fallarán. |

## Ver también

* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)