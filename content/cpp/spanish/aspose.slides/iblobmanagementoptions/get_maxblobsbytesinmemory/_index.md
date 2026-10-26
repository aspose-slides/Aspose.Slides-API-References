---
title: get_MaxBlobsBytesInMemory()
second_title: Referencia de API de Aspose.Slides para C++
description: Define el tamaño total máximo (en bytes) que todos los BLOB pueden ocupar en memoria. Por defecto, todos los BLOB se cargan en memoria; solo cuando se alcanza este límite se emplean mecanismos alternativos (como archivos temporales). Mantener los BLOB en memoria maximiza el rendimiento pero puede generar un alto consumo de memoria. Utilice esta propiedad para adaptar el comportamiento a su entorno o requisitos.
type: docs
weight: 79
url: /es/aspose.slides/iblobmanagementoptions/get_maxblobsbytesinmemory/
---
## IBlobManagementOptions::get_MaxBlobsBytesInMemory() método


Define el tamaño total máximo (en bytes) que todos los BLOB pueden ocupar en memoria. Por defecto, todos los BLOB se cargan en memoria; solo cuando se alcanza este límite se emplean mecanismos alternativos (como archivos temporales). Mantener los BLOB en memoria maximiza el rendimiento pero puede generar un alto consumo de memoria. Utilice esta propiedad para adaptar el comportamiento a su entorno o requisitos.

```cpp
virtual uint64_t Aspose::Slides::IBlobManagementOptions::get_MaxBlobsBytesInMemory()=0
```

## Observaciones


Este valor se ignora si [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) se establece en false, ya que la memoria es entonces la única ubicación de almacenamiento disponible y limitar el uso de BLOB en memoria no tiene efecto. 

El valor predeterminado es 629,145,600 bytes (600 MB). 

Puede establecer esta propiedad en cero, pero todavía se reservará una pequeña cantidad mínima de memoria. 
## Ver también

* Clase [IBlobManagementOptions](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)