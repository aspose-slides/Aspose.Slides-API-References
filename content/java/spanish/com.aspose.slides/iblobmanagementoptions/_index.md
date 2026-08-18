---
title: IBlobManagementOptions
second_title: Aspose.Slides for Java API Reference
description: Un Binary Large Object (BLOB) es un dato binario almacenado como una única entidad, es decir, BLOB puede ser un audio, video o la propia presentación.
type: docs
url: /es/com.aspose.slides/iblobmanagementoptions/
---```
public interface IBlobManagementOptions
```

Un Binary Large Object (BLOB) es un dato binario almacenado como una única entidad, es decir, BLOB puede ser un audio, video o la propia presentación. Se utilizan varias técnicas para optimizar el consumo de memoria al trabajar con BLOBs, que ya estaban almacenados en la presentación o se añaden posteriormente mediante programación. Usando [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) puedes cambiar diferentes aspectos de comportamiento relacionados con el manejo de BLOBs para la vida útil de la instancia [IPresentation](../../com.aspose.slides/ipresentation).
## Métodos

| Método | Descripción |
| --- | --- |
| [getPresentationLockingBehavior()](#getPresentationLockingBehavior--) | Esta propiedad define si una instancia de la clase Presentation puede ser propietaria de la fuente - archivo o flujo durante la vida útil de la instancia. |
| [setPresentationLockingBehavior(int value)](#setPresentationLockingBehavior-int-) | Esta propiedad define si una instancia de la clase Presentation puede ser propietaria de la fuente - archivo o flujo durante la vida útil de la instancia. |
| [isTemporaryFilesAllowed()](#isTemporaryFilesAllowed--) | Esta propiedad define si se pueden crear archivos temporales mientras se trabaja con BLOBs, lo que disminuye considerablemente el consumo de memoria pero requiere permisos para crear archivos. |
| [setTemporaryFilesAllowed(boolean value)](#setTemporaryFilesAllowed-boolean-) | Esta propiedad define si se pueden crear archivos temporales mientras se trabaja con BLOBs, lo que disminuye considerablemente el consumo de memoria pero requiere permisos para crear archivos. |
| [getTempFilesRootPath()](#getTempFilesRootPath--) | La ruta raíz donde se crearán los archivos temporales. |
| [setTempFilesRootPath(String value)](#setTempFilesRootPath-java.lang.String-) | La ruta raíz donde se crearán los archivos temporales. |
| [getMaxBlobsBytesInMemory()](#getMaxBlobsBytesInMemory--) | Define el tamaño total máximo (en bytes) que todos los BLOBs pueden ocupar en memoria. |
| [setMaxBlobsBytesInMemory(long value)](#setMaxBlobsBytesInMemory-long-) | Define el tamaño total máximo (en bytes) que todos los BLOBs pueden ocupar en memoria. |
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
>  // Se lanzará IOException porque pres.pptx está bloqueado durante la vida útil de la Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // después de que el objeto Presentation se elimine, el archivo se desbloquea y puede ser eliminado
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
>  // Se lanzará IOException porque pres.pptx está bloqueado durante la vida útil de la Presentation
>  // java.io.File f = new java.io.File("pres.pptx");
>  // f.delete();
>  // después de que el objeto Presentation se elimine, el archivo se desbloquea y puede ser eliminado
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


Esta propiedad define si se pueden crear archivos temporales mientras se trabaja con BLOBs, lo que disminuye considerablemente el consumo de memoria pero requiere permisos para crear archivos.

--------------------

Todos los archivos se eliminarán después de que se finalice el trabajo con la presentación.

**Devuelve:**
boolean
### setTemporaryFilesAllowed(boolean value) {#setTemporaryFilesAllowed-boolean-}
```
public abstract void setTemporaryFilesAllowed(boolean value)
```


Esta propiedad define si se pueden crear archivos temporales mientras se trabaja con BLOBs, lo que disminuye considerablemente el consumo de memoria pero requiere permisos para crear archivos.

--------------------

Todos los archivos se eliminarán después de que se finalice el trabajo con la presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getTempFilesRootPath() {#getTempFilesRootPath--}
```
public abstract String getTempFilesRootPath()
```


La ruta raíz donde se crearán los archivos temporales. Por defecto se utilizará el directorio temporal del sistema. El proceso de alojamiento debe tener permisos para crear archivos y carpetas allí.

**Devuelve:**
java.lang.String
### setTempFilesRootPath(String value) {#setTempFilesRootPath-java.lang.String-}
```
public abstract void setTempFilesRootPath(String value)
```


La ruta raíz donde se crearán los archivos temporales. Por defecto se utilizará el directorio temporal del sistema. El proceso de alojamiento debe tener permisos para crear archivos y carpetas allí.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getMaxBlobsBytesInMemory() {#getMaxBlobsBytesInMemory--}
```
public abstract long getMaxBlobsBytesInMemory()
```


Define el tamaño total máximo (en bytes) que todos los BLOBs pueden ocupar en memoria. Por defecto, todos los BLOBs se cargan en memoria; solo cuando se alcanza este límite se emplean mecanismos alternativos (como archivos temporales). Mantener los BLOBs en memoria maximiza el rendimiento pero puede generar un alto consumo de memoria. Use esta propiedad para adaptar el comportamiento a su entorno o requisitos.

--------------------

Esta propiedad se ignora si \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) está configurada a false, ya que la memoria es entonces la única ubicación de almacenamiento disponible y limitar el uso de BLOBs en memoria no tiene efecto.

--------------------

El valor predeterminado es 629 145 600 bytes (600 MB).

--------------------

Puede establecer esta propiedad en cero, pero aún se reservará una pequeña cantidad mínima de memoria.

**Devuelve:**
long
### setMaxBlobsBytesInMemory(long value) {#setMaxBlobsBytesInMemory-long-}
```
public abstract void setMaxBlobsBytesInMemory(long value)
```


Define el tamaño total máximo (en bytes) que todos los BLOBs pueden ocupar en memoria. Por defecto, todos los BLOBs se cargan en memoria; solo cuando se alcanza este límite se emplean mecanismos alternativos (como archivos temporales). Mantener los BLOBs en memoria maximiza el rendimiento pero puede generar un alto consumo de memoria. Use esta propiedad para adaptar el comportamiento a su entorno o requisitos.

--------------------

Esta propiedad se ignora si \#isTemporaryFilesAllowed.isTemporaryFilesAllowed/\#setTemporaryFilesAllowed(boolean).setTemporaryFilesAllowed(boolean) está configurada a false, ya que la memoria es entonces la única ubicación de almacenamiento disponible y limitar el uso de BLOBs en memoria no tiene efecto.

--------------------

El valor predeterminado es 629 145 600 bytes (600 MB).

--------------------

Puede establecer esta propiedad en cero, pero aún se reservará una pequeña cantidad mínima de memoria.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |