---
title: BlobManagementOptions
second_title: Aspose.Slides para Android mediante la Referencia de API Java
description: Representa opciones que pueden usarse para gestionar reglas de manejo de BLOB y otras configuraciones de BLOB.
type: docs
url: /es/com.aspose.slides/blobmanagementoptions/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
```
public class BlobManagementOptions implements IBlobManagementOptions
```

Representa opciones que pueden usarse para gestionar reglas de manejo de BLOB y otras configuraciones de BLOB.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [BlobManagementOptions()](#BlobManagementOptions--) | Crea nuevas opciones de gestión de blob predeterminadas. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Esta propiedad define si una instancia de la clase Presentation puede ser propietaria del archivo o flujo fuente durante la vida útil de la instancia. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Esta propiedad define si una instancia de la clase Presentation puede ser propietaria del archivo o flujo fuente durante la vida útil de la instancia. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Esta propiedad define si se pueden crear archivos temporales mientras se trabaja con BLOBs, lo que disminuye enormemente el consumo de memoria pero requiere permisos para crear archivos. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Esta propiedad define si se pueden crear archivos temporales mientras se trabaja con BLOBs, lo que disminuye enormemente el consumo de memoria pero requiere permisos para crear archivos. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | La ruta raíz donde se crearán los archivos temporales. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | La ruta raíz donde se crearán los archivos temporales. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Define el tamaño total máximo (en bytes) que todos los BLOBs pueden ocupar en la memoria. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Define el tamaño total máximo (en bytes) que todos los BLOBs pueden ocupar en la memoria. |

### BlobManagementOptions() {#BlobManagementOptions--}
```
public BlobManagementOptions()
```

Crea nuevas opciones de gestión de blob predeterminadas.

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public final int getPresentationLockingBehavior()
```

Esta propiedad define si una instancia de la clase Presentation puede ser propietaria del archivo o flujo fuente durante la vida útil de la instancia. Si la instancia es propietaria, bloquea la fuente. Esto ayuda a mejorar el consumo de memoria y el rendimiento mientras se trabaja con BLOBs, pero la fuente (flujo o archivo) no puede cambiarse durante la vida útil de la instancia de Presentation.

**Devuelve:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public final void setPresentationLockingBehavior(int value)
```

Esta propiedad define si una instancia de la clase Presentation puede ser propietaria del archivo o flujo fuente durante la vida útil de la instancia. Si la instancia es propietaria, bloquea la fuente. Esto ayuda a mejorar el consumo de memoria y el rendimiento mientras se trabaja con BLOBs, pero la fuente (flujo o archivo) no puede cambiarse durante la vida útil de la instancia de Presentation.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public final boolean isTemporaryFilesAllowed()
```

Esta propiedad define si se pueden crear archivos temporales mientras se trabaja con BLOBs, lo que disminuye enormemente el consumo de memoria pero requiere permisos para crear archivos.

--------------------

Todos los archivos se eliminarán después de que el trabajo con la presentación haya finalizado.

**Devuelve:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public final void setTemporaryFilesAllowed(boolean value)
```

Esta propiedad define si se pueden crear archivos temporales mientras se trabaja con BLOBs, lo que disminuye enormemente el consumo de memoria pero requiere permisos para crear archivos.

--------------------

Todos los archivos se eliminarán después de que el trabajo con la presentación haya finalizado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public final String getTempFilesRootPath()
```

La ruta raíz donde se crearán los archivos temporales. Por defecto se usará el directorio temporal del sistema. El proceso de alojamiento debe tener permisos para crear archivos y carpetas allí.

**Devuelve:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public final void setTempFilesRootPath(String value)
```

La ruta raíz donde se crearán los archivos temporales. Por defecto se usará el directorio temporal del sistema. El proceso de alojamiento debe tener permisos para crear archivos y carpetas allí.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public final long getMaxBlobsBytesInMemory()
```

Define el tamaño total máximo (en bytes) que todos los BLOBs pueden ocupar en la memoria. Por defecto, todos los BLOBs se cargan en memoria; solo cuando se alcanza este límite se emplean mecanismos alternativos (como archivos temporales). Mantener los BLOBs en memoria maximiza el rendimiento pero puede generar un uso elevado de memoria. Utilice esta propiedad para adaptar el comportamiento a su entorno o requisitos.

--------------------

Esta propiedad se ignora si \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) está configurada en false, ya que la memoria es entonces la única ubicación de almacenamiento disponible y limitar el uso de BLOB en memoria no tiene efecto.

--------------------

El valor predeterminado es 629.145.600 bytes (600 MB).

--------------------

Puede establecer esta propiedad en cero, pero aún se reservará una pequeña cantidad mínima de memoria.

**Devuelve:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public final void setMaxBlobsBytesInMemory(long value)
```

Define el tamaño total máximo (en bytes) que todos los BLOBs pueden ocupar en la memoria. Por defecto, todos los BLOBs se cargan en memoria; solo cuando se alcanza este límite se emplean mecanismos alternativos (como archivos temporales). Mantener los BLOBs en memoria maximiza el rendimiento pero puede generar un uso elevado de memoria. Utilice esta propiedad para adaptar el comportamiento a su entorno o requisitos.

--------------------

Esta propiedad se ignora si \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) está configurada en false, ya que la memoria es entonces la única ubicación de almacenamiento disponible y limitar el uso de BLOB en memoria no tiene efecto.

--------------------

El valor predeterminado es 629.145.600 bytes (600 MB).

--------------------

Puede establecer esta propiedad en cero, pero aún se reservará una pequeña cantidad mínima de memoria.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |