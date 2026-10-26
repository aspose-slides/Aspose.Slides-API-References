---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides para Python mediante la API .NET
description: 
type: docs
url: /es/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory propiedad
Defines el tamaño total máximo (en bytes) que todos los BLOBs pueden ocupar en memoria. Por defecto, todos los BLOBs
            se cargan en memoria; solo cuando se alcanza este límite se emplean mecanismos alternativos (como archivos temporales
            archivos) empleados. Mantener los BLOBs en memoria maximiza el rendimiento pero puede generar un alto consumo de memoria. Use
            esta propiedad para adaptar el comportamiento a su entorno o requerimientos.

### Observaciones

Esta propiedad se ignora si [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/es/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) está configurado a false, ya que la memoria es entonces
            la única ubicación de almacenamiento disponible y limitar el uso de BLOBs en memoria no tiene efecto.

### Definición:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```

### Ver también
* clase [`IBlobManagementOptions`](/slides/python-net/es/aspose.slides/iblobmanagementoptions)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)