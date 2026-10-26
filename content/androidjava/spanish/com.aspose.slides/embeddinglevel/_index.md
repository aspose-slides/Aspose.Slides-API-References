---
title: EmbeddingLevel
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Representa los derechos de licencia para incrustar la fuente.
type: docs
url: /es/com.aspose.slides/embeddinglevel/
---
**Herencia:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmbeddingLevel extends System.Enum
```

Representa los derechos de licencia para incrustar la fuente.
## Campos

| Campo | Descripción |
| --- | --- |
| [Installable](#Installable) | Las fuentes con esta configuración indican que pueden ser incrustadas e instaladas permanentemente en el sistema remoto por una aplicación. |
| [Restricted](#Restricted) | Las fuentes que solo tienen este bit activado no deben modificarse, incrustarse ni intercambiarse de ninguna manera sin obtener primero el permiso del propietario legal. |
| [PreviewPrint](#PreviewPrint) | Cuando este bit está activado, la fuente puede ser incrustada y cargada temporalmente en el sistema remoto. |
| [Editable](#Editable) | Cuando este bit está activado, la fuente puede ser incrustada pero solo debe instalarse temporalmente en otros sistemas. |
| [NoSubsetting](#NoSubsetting) | Cuando este bit está activado, la fuente no puede ser subconfigurada antes de incrustarse. |
| [BitmapOnly](#BitmapOnly) | Cuando este bit está activado, solo se pueden incrustar los mapas de bits contenidos en la fuente. |
### Installable {#Installable}
```
public static final int Installable
```

Las fuentes con esta configuración indican que pueden ser incrustadas e instaladas permanentemente en el sistema remoto por una aplicación. El usuario del sistema remoto adquiere los mismos derechos, obligaciones y licencias para esa fuente que el comprador original de la fuente, y está sujeto al mismo acuerdo de licencia de usuario final, derechos de autor, patente de diseño y/o marca registrada que tenía el comprador original.

### Restricted {#Restricted}
```
public static final int Restricted
```

Las fuentes que solo tienen este bit activado no deben modificarse, incrustarse ni intercambiarse de ninguna manera sin obtener primero el permiso del propietario legal.

### PreviewPrint {#PreviewPrint}
```
public static final int PreviewPrint
```

Cuando este bit está activado, la fuente puede ser incrustada y cargada temporalmente en el sistema remoto. Los documentos que contienen fuentes de Vista previa e impresión deben abrirse en modo "solo lectura"; no se pueden aplicar ediciones al documento.

### Editable {#Editable}
```
public static final int Editable
```

Cuando este bit está activado, la fuente puede ser incrustada pero solo debe instalarse temporalmente en otros sistemas. En contraste con las fuentes de Vista previa e impresión, los documentos que contienen fuentes Editables pueden abrirse para lectura, se permite la edición y los cambios pueden guardarse.

### NoSubsetting {#NoSubsetting}
```
public static final int NoSubsetting
```

Cuando este bit está activado, la fuente no puede ser subconfigurada antes de incrustarse. También se aplican otras restricciones de incrustación especificadas en los bits 0-3 y 9.

### BitmapOnly {#BitmapOnly}
```
public static final int BitmapOnly
```

Cuando este bit está activado, solo los mapas de bits contenidos en la fuente pueden incrustarse. No se pueden incrustar datos de contorno. Si no hay mapas de bits disponibles en la fuente, entonces la fuente se considera no incrustable y los servicios de incrustación fallarán.