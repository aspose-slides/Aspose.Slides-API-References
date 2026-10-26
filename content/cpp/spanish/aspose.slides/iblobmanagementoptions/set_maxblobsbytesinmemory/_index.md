---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides para C++ Referencia de la API
description: Define el tamaño total máximo (en bytes) que todos los BLOB pueden ocupar en la memoria. De manera predeterminada, todos los BLOB se cargan en la memoria; solo cuando se alcanza este límite se emplean mecanismos alternativos (como archivos temporales). Mantener los BLOB en memoria maximiza el rendimiento pero puede generar un uso elevado de memoria. Use esta propiedad para adaptar el comportamiento a su entorno o requisitos.
type: docs
weight: 92
url: /es/aspose.slides/iblobmanagementoptions/set_maxblobsbytesinmemory/
---
## IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) método

Define el tamaño total máximo (en bytes) que todos los BLOB pueden ocupar en la memoria. De manera predeterminada, todos los BLOB se cargan en la memoria; solo cuando se alcanza este límite se emplean mecanismos alternativos (como archivos temporales). Mantener los BLOB en memoria maximiza el rendimiento pero puede generar un uso elevado de memoria. Use esta propiedad para adaptar el comportamiento a su entorno o requisitos.

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value)=0
```

## Comentarios

Este valor se ignora si [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) está configurado a false, ya que la memoria es entonces el único lugar de almacenamiento disponible y limitar el uso de BLOB en memoria no tiene efecto. 

El valor predeterminado es 629,145,600 bytes (600 MB). 

Puede establecer esta propiedad a cero, pero aún se reservará una pequeña cantidad mínima de memoria. 

## Ver también

* Clase [IBlobManagementOptions](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)