---
title: IBlobManagementOptions class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions clase

Un Binary Large Object (BLOB) es un dato binario almacenado como una única entidad, es decir, un BLOB puede ser un audio, video o una presentación en sí misma. Se utilizan varias técnicas para optimizar el consumo de memoria al trabajar con BLOBs, ya sea que ya estén almacenados en la presentación o que se agreguen posteriormente de forma programática. Usando [`IBlobManagementOptions`](/slides/python-net/es/aspose.slides/iblobmanagementoptions) puede cambiar diferentes aspectos de comportamiento relacionados con el manejo de BLOBs para la vida útil de la instancia [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation).

El tipo IBlobManagementOptions expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/es/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | Esta propiedad define si una instancia de la clase Presentation puede ser propietaria del archivo o flujo fuente durante la vida de la instancia. Si la instancia es propietaria, bloquea la fuente. Esto ayuda a mejorar el consumo de memoria y el rendimiento al trabajar con BLOBs, pero la fuente (flujo o archivo) no puede cambiarse durante la vida de la instancia de Presentation. Este es un ejemplo: |
| [`is_temporary_files_allowed`](/slides/python-net/es/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | Esta propiedad define si se pueden crear archivos temporales mientras se trabaja con BLOBs, lo que disminuye considerablemente el consumo de memoria pero requiere permisos para crear archivos.<br/>            Todos los archivos se eliminarán después de que el trabajo con la presentación haya finalizado. |
| [`temp_files_root_path`](/slides/python-net/es/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | La ruta raíz donde se crearán los archivos temporales. Por defecto se usará el directorio temporal del sistema.<br/>            El proceso anfitrión debe tener permisos para crear archivos y carpetas allí. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/es/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | Define el tamaño total máximo (en bytes) que todos los BLOBs pueden ocupar en memoria. Por defecto, todos los BLOBs se cargan en memoria; solo cuando se alcanza este límite se emplean mecanismos alternativos (como archivos temporales). Mantener los BLOBs en memoria maximiza el rendimiento pero puede generar un alto uso de memoria. Use esta propiedad para adaptar el comportamiento a su entorno o requisitos. |


### Ver también
* clase [`IBlobManagementOptions`](/slides/python-net/es/aspose.slides/iblobmanagementoptions)
* clase [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)