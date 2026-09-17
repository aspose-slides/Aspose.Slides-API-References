---
title: max_blobs_bytes_in_memory property
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory propiedad
Define el tamaño total máximo (en bytes) que todos los BLOBs pueden ocupar en la memoria. Por defecto, todos los BLOBs
            se cargan en la memoria; solo cuando se alcanza este límite se emplean mecanismos alternativos (como archivos temporales)
            Mantener los BLOBs en la memoria maximiza el rendimiento pero puede provocar un alto consumo de memoria. Use
            esta propiedad para adaptar el comportamiento a su entorno o requisitos.


### Remarks

Esta propiedad se ignora si [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/es/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) está configurado a false, ya que la memoria es entonces
            la única ubicación de almacenamiento disponible y limitar el uso de BLOBs en memoria no tiene efecto.

### Definition:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```


### See Also
* clase [`BlobManagementOptions`](/slides/python-net/es/aspose.slides/blobmanagementoptions)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)