---
title: SetEmbeddedData
second_title: Aspose.Slides para .NET Referencia de la API
description: Establece información sobre datos OLE incrustados. Este método cambia las propiedades del objeto para reflejar los nuevos datos y establece la bandera IsObjectLink en falso, indicando que el objeto OLE está incrustado.
type: docs
weight: 150
url: /es/aspose.slides/oleobjectframe/setembeddeddata/
---

## OleObjectFrame.SetEmbeddedData método

Establece información sobre datos OLE incrustados. Este método cambia las propiedades del objeto para reflejar los nuevos datos y establece la bandera IsObjectLink en falso, indicando que el objeto OLE está incrustado.

```csharp
public void SetEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| embeddedData | IOleEmbeddedDataInfo | Datos incrustados [`IOleEmbeddedDataInfo`](../../ioleembeddeddatainfo) |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Cuando el parámetro embeddedData es nulo. |

### Ejemplos

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

### Ver También

* interfaz [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo)
* clase [OleObjectFrame](../../oleobjectframe)
* espacio de nombres [Aspose.Slides](../../oleobjectframe)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->