---
title: MaxBlobsBytesInMemory
second_title: Referencia de API de Aspose.Slides para .NET
description: Define la cantidad máxima en bytes que todos los BLOBs en total pueden ocupar en memoria. Primero, todos los BLOBs se cargan en memoria como comportamiento predeterminado y solo cuando se alcanza el límite definido por esta propiedad, se pueden involucrar otros mecanismos, como archivos temporales. En términos de rendimiento, la forma más eficiente es almacenar BLOBs en memoria, pero por el otro lado, esto conlleva un alto consumo de memoria, lo que puede ser indeseable. Usando esta propiedad, puedes establecer el comportamiento óptimo para tu entorno u otros requisitos. Esta propiedad será ignorada si IsTemporaryFilesAllowed../istemporaryfilesallowed se establece en false. No tiene sentido limitar la cantidad máxima de BLOBs en memoria, porque si IsTemporaryFilesAllowed../istemporaryfilesallowed se establece en false, la memoria es el único lugar donde se pueden almacenar los BLOBs. El valor predeterminado es 629,145,600 bytes 600Mb.
type: docs
weight: 30
url: /es/aspose.slides/blobmanagementoptions/maxblobsbytesinmemory/
---

## Propiedad BlobManagementOptions.MaxBlobsBytesInMemory

Define la cantidad máxima (en bytes) que todos los BLOBs en total pueden ocupar en memoria. Primero, todos los BLOBs se cargan en memoria como comportamiento predeterminado y solo cuando se alcanza el límite definido por esta propiedad, se pueden involucrar otros mecanismos (como archivos temporales). En términos de rendimiento, la forma más eficiente es almacenar BLOBs en memoria, pero por el otro lado, esto conlleva un alto consumo de memoria, lo que puede ser indeseable. Usando esta propiedad, puedes establecer el comportamiento óptimo para tu entorno u otros requisitos. Esta propiedad será ignorada si [`IsTemporaryFilesAllowed`](../istemporaryfilesallowed) se establece en false. No tiene sentido limitar la cantidad máxima de BLOBs en memoria, porque si [`IsTemporaryFilesAllowed`](../istemporaryfilesallowed) se establece en false, la memoria es el único lugar donde se pueden almacenar los BLOBs. El valor predeterminado es 629,145,600 bytes (600Mb).

```csharp
public ulong MaxBlobsBytesInMemory { get; set; }
```

### Véase también

* clase [BlobManagementOptions](../../blobmanagementoptions)
* espacio de nombres [Aspose.Slides](../../blobmanagementoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->