---
title: IBlobManagementOptions
second_title: Aspose.Slides para Android mediante la referencia de API de Java
description: Un Binary Large Object (BLOB) es un dato binario almacenado como una única entidad - es decir.
type: docs
url: /es/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Un Binary Large Object (BLOB) es un dato binario almacenado como una única entidad - es decir, BLOB puede ser un audio, un video o la propia presentación. Se utilizan varias técnicas para optimizar el consumo de memoria al trabajar con BLOBs, que ya están almacenados en la presentación o que se pueden añadir posteriormente mediante programación. Usando [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) puedes cambiar diferentes aspectos de comportamiento relativos al manejo de BLOBs para la vida útil de la instancia [IPresentation](../../com.aspose.slides/ipresentation).

## Métodos

| Método | Descripción |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Esta propiedad define si una instancia de la clase Presentation puede ser propietaria de la fuente - archivo o flujo durante la vida útil de la instancia. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Esta propiedad define si una instancia de la clase Presentation puede ser propietaria de la fuente - archivo o flujo durante la vida útil de la instancia. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Esta propiedad define si se pueden crear archivos temporales al trabajar con BLOBs, lo que disminuye considerablemente el consumo de memoria pero requiere permisos para crear archivos. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Esta propiedad define si se pueden crear archivos temporales al trabajar con BLOBs, lo que disminuye considerablemente el consumo de memoria pero requiere permisos para crear archivos. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | La ruta raíz donde se crearán los archivos temporales. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | La ruta raíz donde se crearán los archivos temporales. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Define el tamaño total máximo (en bytes) que todos los BLOB pueden ocupar en memoria. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Define el tamaño total máximo (en bytes) que todos los BLOB pueden ocupar en memoria. |

### getPresentationLockingBehavior() {#getPresentationLockingBehavior--}
```
public abstract int getPresentationLockingBehavior()
```

Esta propiedad define si una instancia de la clase Presentation puede ser propietaria de la fuente - archivo o flujo durante la vida útil de la instancia. Si la instancia es propietaria, bloquea la fuente. Esto ayuda a mejorar el consumo de memoria y el rendimiento al trabajar con BLOBs, pero la fuente (flujo o archivo) no puede cambiarse durante la vida útil de la instancia Presentation. Este es un ejemplo:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // Se lanzará IOException porque pres.pptx está bloqueado durante la vida de la Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // después de que el objeto Presentation se elimine, el archivo se desbloquea y puede ser borrado
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Devuelve:**
int

### setPresentationLockingBehavior(int value) {#setPresentationLockingBehavior-int-}
```
public abstract void setPresentationLockingBehavior(int value)
```

Esta propiedad define si una instancia de la clase Presentation puede ser propietaria de la fuente - archivo o flujo durante la vida útil de la instancia. Si la instancia es propietaria, bloquea la fuente. Esto ayuda a mejorar el consumo de memoria y el rendimiento al trabajar con BLOBs, pero la fuente (flujo o archivo) no puede cambiarse durante la vida útil de la instancia Presentation. Este es un ejemplo:

--------------------

> ```
> LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  // Se lanzará IOException porque pres.pptx está bloqueado durante la vida de la Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // después de que el objeto Presentation se elimine, el archivo se desbloquea y puede ser borrado
>  java.io.File f = new java.io.File("pres.pptx");
>  f.delete();
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### isTemporaryFilesAllowed() {#isTemporaryFilesAllowed--}
```
public abstract boolean isTemporaryFilesAllowed()
```

Esta propiedad define si se pueden crear archivos temporales al trabajar con BLOBs, lo que disminuye considerablemente el consumo de memoria pero requiere permisos para crear archivos.

--------------------

Todos los archivos se eliminarán una vez finalizado el trabajo con la presentación.

**Devuelve:**
boolean

### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```

Esta propiedad define si se pueden crear archivos temporales al trabajar con BLOBs, lo que disminuye considerablemente el consumo de memoria pero requiere permisos para crear archivos.

--------------------

Todos los archivos se eliminarán una vez finalizado el trabajo con la presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```

La ruta raíz donde se crearán los archivos temporales. Por defecto se usará el directorio temporal del sistema. El proceso anfitrión debe tener permisos para crear archivos y carpetas allí.

**Devuelve:**
java.lang.String

### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```

La ruta raíz donde se crearán los archivos temporales. Por defecto se usará el directorio temporal del sistema. El proceso anfitrión debe tener permisos para crear archivos y carpetas allí.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```

Define el tamaño total máximo (en bytes) que todos los BLOB pueden ocupar en memoria. Por defecto, todos los BLOB se cargan en memoria; solo cuando se alcanza este límite se emplean mecanismos alternativos (como archivos temporales). Mantener los BLOB en memoria maximiza el rendimiento pero puede generar un alto uso de memoria. Usa esta propiedad para adaptar el comportamiento a tu entorno o requisitos.

--------------------

Esta propiedad se ignora si \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) está establecida en false, ya que entonces la memoria es la única ubicación de almacenamiento disponible y limitar el uso de BLOB en memoria no tiene efecto.

--------------------

El valor predeterminado es 629,145,600 bytes (600 MB).

--------------------

Puedes establecer esta propiedad en cero, pero aun así se reservará una pequeña cantidad mínima de memoria.

**Devuelve:**
long

### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```

Define el tamaño total máximo (en bytes) que todos los BLOB pueden ocupar en memoria. Por defecto, todos los BLOB se cargan en memoria; solo cuando se alcanza este límite se emplean mecanismos alternativos (como archivos temporales). Mantener los BLOB en memoria maximiza el rendimiento pero puede generar un alto uso de memoria. Usa esta propiedad para adaptar el comportamiento a tu entorno o requisitos.

--------------------

Esta propiedad se ignora si \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) está establecida en false, ya que entonces la memoria es la única ubicación de almacenamiento disponible y limitar el uso de BLOB en memoria no tiene efecto.

--------------------

El valor predeterminado es 629,145,600 bytes (600 MB).

--------------------

Puedes establecer esta propiedad en cero, pero aun así se reservará una pequeña cantidad mínima de memoria.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |