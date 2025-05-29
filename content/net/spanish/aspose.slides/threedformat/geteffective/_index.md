---
title: GetEffective
second_title: Referencia de la API de Aspose.Slides para .NET
description: Obtiene datos de formato 3-D efectivo con la herencia aplicada.
type: docs
weight: 110
url: /es/aspose.slides/threedformat/geteffective/
---

## Método ThreeDFormat.GetEffective

Obtiene datos de formato 3-D efectivo con la herencia aplicada.

```csharp
public IThreeDFormatEffectiveData GetEffective()
```

### Valor de Retorno

Un [`IThreeDFormatEffectiveData`](../../ithreedformateffectivedata).

### Ejemplos

Este ejemplo demuestra cómo obtener propiedades efectivas para la cámara, el equipo de iluminación y el bisel superior de la forma.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
    IThreeDFormatEffectiveData threeDEffectiveData = pres.Slides[0].Shapes[0].ThreeDFormat.GetEffective();

    Console.WriteLine("= Propiedades efectivas de la cámara =");
    Console.WriteLine("Tipo: " + threeDEffectiveData.Camera.CameraType);
    Console.WriteLine("Campo de visión: " + threeDEffectiveData.Camera.FieldOfViewAngle);
    Console.WriteLine("Zoom: " + threeDEffectiveData.Camera.Zoom);

    Console.WriteLine("= Propiedades efectivas del equipo de iluminación =");
    Console.WriteLine("Tipo: " + threeDEffectiveData.LightRig.LightType);
    Console.WriteLine("Dirección: " + threeDEffectiveData.LightRig.Direction);

    Console.WriteLine("= Propiedades efectivas del relieve de la cara superior de la forma =");
    Console.WriteLine("Tipo: " + threeDEffectiveData.BevelTop.BevelType);
    Console.WriteLine("Ancho: " + threeDEffectiveData.BevelTop.Width);
    Console.WriteLine("Altura: " + threeDEffectiveData.BevelTop.Height);
}
```

### Véase También

* interfaz [IThreeDFormatEffectiveData](../../ithreedformateffectivedata)
* clase [ThreeDFormat](../../threedformat)
* espacio de nombres [Aspose.Slides](../../threedformat)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->