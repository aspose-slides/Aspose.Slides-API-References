---
title: SetEmbeddedData
second_title: Referencia de la API de Aspose.Slides para .NET
description: Establece información sobre datos OLE embebidos.
type: docs
weight: 150
url: /es/aspose.slides/ioleobjectframe/setembeddeddata/
---

## Método IOleObjectFrame.SetEmbeddedData

Establece información sobre datos OLE embebidos.

```csharp
public void SetEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| embeddedData | IOleEmbeddedDataInfo | Datos embebidos [`IOleEmbeddedDataInfo`](../../ioleembeddeddatainfo) |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Cuando el parámetro embeddedData es nulo. |

### Observaciones

Este método cambia las propiedades del objeto para reflejar los nuevos datos y establece la bandera IsObjectLink a falso, indicando que el objeto OLE está embebido.

### Ejemplos

El siguiente ejemplo demuestra cómo cambiar los datos OLE embebidos y su tipo para un objeto existente [`IOleObjectFrame`](../../ioleobjectframe)

```csharp
[C#]
using (Presentation pres = new Presentation("SomePresentation.pptx"))
{
    OleObjectFrame oof = pres.Slides[0].Shapes[0] as OleObjectFrame;
    if (oof != null)
    {
        IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(File.ReadAllBytes("Picture.png"), "png");
        oof.SetEmbeddedData(newData);
    }
}
```

### Véase también

* interfaz [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo)
* interfaz [IOleObjectFrame](../../ioleobjectframe)
* espacio de nombres [Aspose.Slides](../../ioleobjectframe)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->