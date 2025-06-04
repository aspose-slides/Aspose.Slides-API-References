---
title: DeleteEmbeddedBinaryObjects
second_title: Aspose.Slides para .NET Referencia de API
description: Determina si Aspose.Slides eliminará todos los objetos binarios incrustados al cargar la presentación.
type: docs
weight: 70
url: /es/aspose.slides/loadoptions/deleteembeddedbinaryobjects/
---

## LoadOptions.DeleteEmbeddedBinaryObjects propiedad

Determina si Aspose.Slides eliminará todos los objetos binarios incrustados al cargar la presentación.

Los tipos de los objetos binarios incrustados:

* Proyecto VBA [`VbaProject`](../../ipresentation/vbaproject)
* Datos de objeto OLE incrustados [`EmbeddedFileData`](../../ioleembeddeddatainfo/embeddedfiledata)
* Datos binarios de Control ActiveX [`ActiveXControlBinary`](../../icontrol/activexcontrolbinary)

Lectura/escritura Booleano.

```csharp
public bool DeleteEmbeddedBinaryObjects { get; set; }
```

### Observaciones

El valor predeterminado es **false**.

### Ejemplos

El siguiente ejemplo muestra cómo cargar la presentación sin ningún objeto binario incrustado.

```csharp
[C#]
LoadOptions loadOptions = new LoadOptions();
loadOptions.DeleteEmbeddedBinaryObjects = true;
using (Presentation pres = new Presentation("pres.ppt", loadOptions))
{
    pres.Save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
}
```

### Véase también

* clase [LoadOptions](../../loadoptions)
* espacio de nombres [Aspose.Slides](../../loadoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->