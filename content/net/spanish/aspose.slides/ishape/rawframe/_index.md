---
title: RawFrame
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve o establece las propiedades de los marcos de forma en bruto. Lectura/escritura IShapeFrameaspose.slides/ishapeframe.
type: docs
weight: 210
url: /es/aspose.slides/ishape/rawframe/
---

## Propiedad IShape.RawFrame

Devuelve o establece las propiedades del marco de forma en bruto. Lectura/escritura [`IShapeFrame`](../../ishapeframe).

```csharp
public IShapeFrame RawFrame { get; set; }
```

### Ejemplos

El código que intenta asignar un marco indefinido a IShape.Frame no tiene sentido en el caso general (particularmente en el caso en que el GroupShape padre está anidado múltiples veces en otros GroupShape). Por ejemplo:

```csharp
IShape shape = ...;
shape.Frame = new ShapeFrame(float.NaN, float.NaN, float.NaN, float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, float.NaN);
```

o

```csharp
slide.Shapes.AddAutoShape(ShapeType.RoundCornerRectangle, float.NaN, float.NaN, float.NaN, float.NaN);
```

Este tipo de código puede llevar a situaciones confusas. Así que se han añadido restricciones para usar valores indefinidos para IShape.Frame. Los valores de x, y, ancho, alto, flipH, flipV y rotationAngle deben estar definidos (no pueden ser float.NaN o NullableBool.NotDefined). El código de ejemplo anterior ahora lanza una excepción ArgumentException. Esto se aplica a estos casos de uso:

```csharp
IShape shape = ...;
shape.Frame = ...; // no puede ser indefinido

IShapeCollection shapes = ...;
// los parámetros x, y, ancho, alto no pueden ser float.NaN:
{
    shapes.AddAudioFrameCD(...);
    shapes.AddAudioFrameEmbedded(...);
    shapes.AddAudioFrameLinked(...);
    shapes.AddAutoShape(...);
    shapes.AddChart(...);
    shapes.AddConnector(...);
    shapes.AddOleObjectFrame(...);
    shapes.AddPictureFrame(...);
    shapes.AddSmartArt(...);
    shapes.AddTable(...);
    shapes.AddVideoFrame(...);
    shapes.InsertAudioFrameEmbedded(...);
    shapes.InsertAudioFrameLinked(...);
    shapes.InsertAutoShape(...);
    shapes.InsertChart(...);
    shapes.InsertConnector(...);
    shapes.InsertOleObjectFrame(...);
    shapes.InsertPictureFrame(...);
    shapes.InsertTable(...);
    shapes.InsertVideoFrame(...);
}
```

Pero las propiedades del marco de IShape.RawFrame pueden ser indefinidas. Esto tiene sentido cuando la forma está vinculada a un placeholder. Entonces, los valores del marco de forma indefinidos se reemplazan desde la forma del placeholder padre. Si no hay una forma de placeholder padre para esa forma, entonces esa forma usa valores predeterminados cuando evalúa el marco efectivo basado en su IShape.RawFrame. Los valores predeterminados son 0 y NullableBool.False para x, y, ancho, alto, flipH, flipV y rotationAngle. Por ejemplo:

```csharp
IShape shape = ...; // la forma está vinculada a un placeholder
shape.RawFrame = new ShapeFrame(float.NaN, float.NaN, 100, float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0); // ahora la forma hereda los valores x, y, alto, flipH, flipV del placeholder y sobrescribe ancho=100 y rotationAngle=0.
```

### Ver También

* interfaz [IShapeFrame](../../ishapeframe)
* interfaz [IShape](../../ishape)
* espacio de nombres [Aspose.Slides](../../ishape)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->