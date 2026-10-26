---
title: EmbeddingLevel enumeration
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/embeddinglevel/
---
## EmbeddingLevel enumeración

Representa los derechos de licencia para incrustar la fuente.

El tipo EmbeddingLevel expone los siguientes miembros:

## Campos

| Campo | Descripción |
| :- | :- |
| INSTALLABLE | Las fuentes con esta configuración indican que pueden ser incrustadas e instaladas permanentemente en el sistema remoto por una aplicación. <br/>            El usuario del sistema remoto adquiere los mismos derechos, obligaciones y licencias para esa fuente que el comprador original de la fuente, <br/>            y está sujeto al mismo acuerdo de licencia de usuario final, derechos de autor, patente de diseño y/o marca registrada que tenía el comprador original. |
| RESTRICTED | Las fuentes que solo tienen este bit activado no deben ser modificadas, incrustadas o intercambiadas de ninguna manera sin obtener primero el permiso del propietario legal. |
| PREVIEW_PRINT | Cuando este bit está activado, la fuente puede ser incrustada y cargada temporalmente en el sistema remoto. Los documentos que contienen fuentes Preview & <br/>            Print deben abrirse en "solo lectura"; no se pueden aplicar ediciones al documento. |
| EDITABLE | Cuando este bit está activado, la fuente puede ser incrustada pero solo debe instalarse temporalmente en otros sistemas. En contraste con las fuentes Preview & <br/>            Print, los documentos que contienen fuentes Editable pueden abrirse para lectura, la edición está permitida y los cambios pueden guardarse. |
| NO_SUBSETTING | Cuando este bit está activado, la fuente no puede ser sub-conjuntada antes de incrustarla. Otras restricciones de incrustación especificadas en los bits 0-3 y 9 también se aplican. |
| BITMAP_ONLY | Cuando este bit está activado, solo se pueden incrustar los mapas de bits contenidos en la fuente. No se pueden incrustar datos de contorno. Si no hay mapas de bits disponibles en la fuente, <br/>            entonces la fuente se considera no incrustable y los servicios de incrustación fallarán. |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)