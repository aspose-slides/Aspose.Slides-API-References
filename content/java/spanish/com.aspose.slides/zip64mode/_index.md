---
title: Zip64Mode
second_title: Referencia de API de Aspose.Slides para Java
description: Especifica cuándo usar extensiones de formato ZIP64 para un archivo OpenXML.
type: docs
url: /es/com.aspose.slides/zip64mode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

Especifica cuándo usar extensiones de formato ZIP64 para un archivo OpenXML.

--------------------

Un archivo OpenXML es un archivo ZIP que tiene un límite de 4 GB (2^32 bytes) para el tamaño sin comprimir de un archivo, el tamaño comprimido de un archivo y el tamaño total del archivo, así como un límite de 65 535 (2^16-1) archivos en el archivo. Las extensiones de formato ZIP64 aumentan los límites a 2^64.
## Campos

| Campo | Descripción |
| --- | --- |
| [Never](#Never) | Do not use ZIP64 format extensions. |
| [IfNecessary](#IfNecessary) | Use ZIP64 format extensions if necessary. |
| [Always](#Always) | Always use ZIP64 format extensions. |
### Never {#Never}
```
public static final int Never
```

No use extensiones de formato ZIP64.

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```

Use extensiones de formato ZIP64 si es necesario.

### Always {#Always}
```
public static final int Always
```

Siempre use extensiones de formato ZIP64.