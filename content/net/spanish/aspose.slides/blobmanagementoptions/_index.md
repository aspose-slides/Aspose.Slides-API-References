---
title: BlobManagementOptions
second_title: Referencia API de Aspose.Slides para .NET
description: Representa opciones que pueden ser utilizadas para gestionar las reglas de manejo de BLOB y otros ajustes de BLOB.
type: docs
weight: 950
url: /es/aspose.slides/blobmanagementoptions/
---

## Clase BlobManagementOptions

Representa opciones que pueden ser utilizadas para gestionar las reglas de manejo de BLOB y otros ajustes de BLOB.

```csharp
public class BlobManagementOptions : IBlobManagementOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [BlobManagementOptions](blobmanagementoptions)() | Crea nuevas opciones de gestión de BLOB predeterminadas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsTemporaryFilesAllowed](../../aspose.slides/blobmanagementoptions/istemporaryfilesallowed) { get; set; } | Esta propiedad define si se pueden crear archivos temporales mientras se trabaja con BLOBs, lo que reduce considerablemente el consumo de memoria pero requiere permisos para crear archivos. Todos los archivos se eliminarán después de que se haya terminado el trabajo con la presentación. |
| [MaxBlobsBytesInMemory](../../aspose.slides/blobmanagementoptions/maxblobsbytesinmemory) { get; set; } | Define la cantidad máxima (en bytes) que todos los BLOBs en total pueden ocupar en la memoria. Primero, todos los BLOBs se cargan en la memoria como comportamiento predeterminado y solo cuando se alcanza el límite definido por esta propiedad, se pueden involucrar otros mecanismos (como archivos temporales). En términos de rendimiento, la forma más eficiente es almacenar BLOBs en memoria, pero por otro lado, esto conlleva a un alto consumo de memoria, lo que puede ser indeseable. Usando esta propiedad, puede establecer el comportamiento óptimo para su entorno u otros requisitos. Esta propiedad será ignorada si [`IsTemporaryFilesAllowed`](./istemporaryfilesallowed) se establece en false. No tiene sentido limitar la cantidad máxima de BLOBs en memoria, porque si [`IsTemporaryFilesAllowed`](./istemporaryfilesallowed) se establece en false, la memoria es el único lugar donde se pueden almacenar los BLOBs. El valor predeterminado es 629,145,600 bytes (600Mb). |
| [PresentationLockingBehavior](../../aspose.slides/blobmanagementoptions/presentationlockingbehavior) { get; set; } | Esta propiedad define si una instancia de la clase Presentation puede ser dueña de la fuente - archivo o flujo durante la duración de la instancia. Si la instancia es dueña, bloquea la fuente. Esto ayuda a mejorar el consumo de memoria y el rendimiento mientras se trabaja con BLOBs, pero la fuente (flujo o archivo) no puede cambiarse durante la duración de la instancia de Presentation. |
| [TempFilesRootPath](../../aspose.slides/blobmanagementoptions/tempfilesrootpath) { get; set; } | La ruta raíz donde se crearán los archivos temporales. Se utilizará el directorio temporal del sistema por defecto. El proceso de hospedaje debe tener permisos para crear archivos y carpetas allí. |

### Ver También

* interface [IBlobManagementOptions](../iblobmanagementoptions)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->