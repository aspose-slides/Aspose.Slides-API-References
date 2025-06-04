---
title: MaxBlobsBytesInMemory
second_title: Aspose.Slides para .NET Referencia de API
description: Define la cantidad máxima en bytes que todos los BLOBs en total pueden ocupar en memoria. Primero, todos los BLOBs se cargan en memoria como comportamiento predeterminado y solo cuando alcanza el límite definido por esta propiedad se pueden involucrar otros mecanismos, como archivos temporales. En términos de rendimiento, la forma más eficiente es almacenar BLOBs en memoria, pero por otro lado, esto lleva a un alto consumo de memoria, lo que puede ser indeseable. Usando esta propiedad, puedes establecer el comportamiento óptimo para tu entorno u otros requisitos. Esta propiedad se ignorará si IsTemporaryFilesAllowed../istemporaryfilesallowed está configurada en false. No tiene sentido limitar la cantidad máxima de BLOBs en memoria, porque si IsTemporaryFilesAllowed../istemporaryfilesallowed está configurada en false, la memoria es el único lugar donde se pueden almacenar los BLOBs. El valor predeterminado es 629,145,600 bytes 600Mb.
type: docs
weight: 20
url: /es/aspose.slides/iblobmanagementoptions/maxblobsbytesinmemory/
---

## IBlobManagementOptions.MaxBlobsBytesInMemory propiedad

Define la cantidad máxima (en bytes) que todos los BLOBs en total pueden ocupar en memoria. Primero, todos los BLOBs se cargan en memoria como comportamiento predeterminado y solo cuando alcanza el límite definido por esta propiedad, se pueden involucrar otros mecanismos (como archivos temporales). En términos de rendimiento, la forma más eficiente es almacenar BLOBs en memoria, pero por otro lado, esto lleva a un alto consumo de memoria, lo que puede ser indeseable. Usando esta propiedad, puedes establecer el comportamiento óptimo para tu entorno u otros requisitos. Esta propiedad se ignorará si [`IsTemporaryFilesAllowed`](../istemporaryfilesallowed) está configurada en false. No tiene sentido limitar la cantidad máxima de BLOBs en memoria, porque si [`IsTemporaryFilesAllowed`](../istemporaryfilesallowed) está configurada en false, la memoria es el único lugar donde se pueden almacenar los BLOBs. El valor predeterminado es 629,145,600 bytes (600Mb).

```csharp
public ulong MaxBlobsBytesInMemory { get; set; }
```

### Ver También

* interfaz [IBlobManagementOptions](../../iblobmanagementoptions)
* espacio de nombres [Aspose.Slides](../../iblobmanagementoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->