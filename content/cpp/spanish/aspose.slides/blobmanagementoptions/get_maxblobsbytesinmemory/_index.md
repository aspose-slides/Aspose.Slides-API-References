---
title: get_MaxBlobsBytesInMemory()
second_title: Referencia de API de Aspose.Slides para C++
description: Define el tamaño total máximo (en bytes) que todos los BLOB pueden ocupar en memoria. Por defecto, todos los BLOB se cargan en memoria; solo cuando se alcanza este límite se emplean mecanismos alternativos (como archivos temporales). Mantener los BLOB en memoria maximiza el rendimiento pero puede generar un alto consumo de memoria. Use esta propiedad para adaptar el comportamiento a su entorno o requisitos.
type: docs
weight: 79
url: /es/aspose.slides/blobmanagementoptions/get_maxblobsbytesinmemory/
---
## BlobManagementOptions::get_MaxBlobsBytesInMemory() método


Define el tamaño total máximo (en bytes) que todos los BLOB pueden ocupar en memoria. Por defecto, todos los BLOB se cargan en memoria; solo cuando se alcanza este límite se emplean mecanismos alternativos (como archivos temporales). Mantener los BLOB en memoria maximiza el rendimiento pero puede generar un alto consumo de memoria. Use esta propiedad para adaptar el comportamiento a su entorno o requisitos.

```cpp
uint64_t Aspose::Slides::BlobManagementOptions::get_MaxBlobsBytesInMemory() override
```

## Observaciones


Este valor se ignora si [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) está configurado en false, ya que la memoria es entonces la única ubicación de almacenamiento disponible y limitar el uso en memoria de BLOB no tiene efecto. 

El valor predeterminado es 629,145,600 bytes (600 MB). 

Puede establecer esta propiedad en cero, pero una pequeña cantidad mínima de memoria seguirá reservada. 
## Véase también

* Clase [BlobManagementOptions](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)