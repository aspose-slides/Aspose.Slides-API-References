---
title: BlobManagementOptions class
second_title: Referencia de la API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions clase

Representa opciones que pueden usarse para administrar las reglas de manejo de BLOB y otras configuraciones de BLOB.

El tipo BlobManagementOptions expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides/blobmanagementoptions/__init__/#) | Crea nuevas opciones de gestión de blob predeterminadas. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/es/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | Esta propiedad define si una instancia de la clase Presentation puede ser propietaria del archivo fuente <br/>            o flujo durante la vida útil de la instancia. Si la instancia es propietaria, bloquea la fuente. Esto ayuda <br/>            a mejorar el consumo de memoria y el rendimiento al trabajar con BLOBs, pero la fuente (flujo o archivo) <br/>            no puede cambiarse durante la vida útil de la instancia de Presentation. |
| [`is_temporary_files_allowed`](/slides/python-net/es/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | Esta propiedad define si pueden crearse archivos temporales al trabajar con BLOBs, lo que reduce considerablemente <br/>            el consumo de memoria pero requiere permisos para crear archivos.<br/>            Todos los archivos serán eliminados después de que el trabajo con la presentación haya finalizado. |
| [`temp_files_root_path`](/slides/python-net/es/aspose.slides/blobmanagementoptions/temp_files_root_path/) | La ruta raíz donde se crearán los archivos temporales. Se utilizará el directorio temporal del sistema por defecto. <br/>            El proceso de alojamiento debe tener permisos para <br/>            crear archivos y carpetas allí. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/es/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | Define el tamaño total máximo (en bytes) que todos los BLOB pueden ocupar en memoria. Por defecto, todos los BLOB<br/>            se cargan en memoria; solo cuando se alcanza este límite se emplean mecanismos alternativos (como archivos temporales). Mantener los BLOB en memoria maximiza el rendimiento pero puede generar un alto uso de memoria. Use<br/>            esta propiedad para adaptar el comportamiento a su entorno o requisitos. |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)