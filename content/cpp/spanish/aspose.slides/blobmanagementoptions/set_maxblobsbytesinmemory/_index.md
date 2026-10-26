---
title: set_MaxBlobsBytesInMemory()
second_title: Referencia de API de Aspose.Slides para C++
description: Define el tamaño total máximo (en bytes) que todos los BLOBs pueden ocupar en la memoria. Por defecto, todos los BLOBs se cargan en la memoria; solo cuando se alcanza este límite se emplean mecanismos alternativos (como archivos temporales). Mantener los BLOBs en la memoria maximiza el rendimiento pero puede generar un alto consumo de memoria. Utilice esta propiedad para adaptar el comportamiento a su entorno o requisitos.
type: docs
weight: 92
url: /es/aspose.slides/blobmanagementoptions/set_maxblobsbytesinmemory/
---
## BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) método


Define el tamaño total máximo (en bytes) que todos los BLOBs pueden ocupar en la memoria. Por defecto, todos los BLOBs se cargan en la memoria; solo cuando se alcanza este límite se emplean mecanismos alternativos (como archivos temporales). Mantener los BLOBs en la memoria maximiza el rendimiento pero puede provocar un alto consumo de memoria. Utilice esta propiedad para adaptar el comportamiento a su entorno o requisitos.

```cpp
void Aspose::Slides::BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value) override
```

## Observaciones


Este valor se ignora si [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) está configurado en false, ya que la memoria es entonces la única ubicación de almacenamiento disponible y limitar el uso de BLOBs en memoria no tiene efecto. 

El valor predeterminado es 629,145,600 bytes (600 MB). 

Puede establecer esta propiedad en cero, pero aún se reservará una pequeña cantidad mínima de memoria. 
## Ver también

* Clase [BlobManagementOptions](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)