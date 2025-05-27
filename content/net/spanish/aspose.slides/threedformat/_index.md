---
title: ThreeDFormat
second_title: Aspose.Sildes para .NET Referencia de API
description: Representa propiedades 3-D.
type: docs
weight: 11180
url: /es/aspose.slides/threedformat/
---

## Clase ThreeDFormat

Representa propiedades 3-D.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obtener la interfaz base IPresentationComponent. Solo lectura [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | Devuelve o establece el tipo de un bisel 3D inferior. Solo lectura [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | Devuelve o establece el tipo de un bisel 3D superior. Solo lectura [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | Devuelve o establece la configuración de una cámara. Solo lectura [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | Devuelve o establece el color de un contorno. Solo lectura [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | Devuelve o establece el ancho de un contorno 3D. Lectura/escritura Doble. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | Devuelve o establece la profundidad de una forma 3D. Lectura/escritura Doble. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | Devuelve o establece el color de una extrusión. Solo lectura [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | Devuelve o establece la altura de un efecto de extrusión. Lectura/escritura Doble. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | Devuelve o establece el tipo de una luz. Solo lectura [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | Devuelve o establece el tipo de un material. Lectura/escritura [`MaterialPresetType`](../materialpresettype). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara con el objeto especificado. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | Obtiene los datos de formato 3-D efectivos con la herencia aplicada. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Devuelve el código hash. |

### Ejemplos

El siguiente ejemplo muestra cómo agregar una forma 3D en una presentación de PowerPoint.

```csharp
[C#]
// Crear una instancia de la clase Presentation.
using (Presentation pres = new Presentation())
{
	// Agregar una forma utilizando el método AddAutoShape
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// Definir TextFrame y sus propiedades
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Definir propiedades de ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Guardar el archivo de la presentación
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

El siguiente ejemplo muestra cómo aplicar un efecto de degradado a una forma 3D en una presentación de PowerPoint.

```csharp
[C#]
// Crear una instancia de la clase Presentation.
using (Presentation pres = new Presentation())
{
	// Agregar una forma utilizando el método AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Definir TextFrame y sus propiedades
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Configurar FillFormat.FillType como FillType.Gradient y definir propiedades de gradiente
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// Definir propiedades de ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Guardar el archivo de la presentación
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

El siguiente ejemplo muestra cómo aplicar un efecto 3D en el texto. Para crear un texto 3D, es posible usar el efecto de transformación de WordArt.

```csharp
[C#]
// Crear una instancia de la clase Presentation.
using (Presentation pres = new Presentation())
{
	// Agregar una forma utilizando el método AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Definir TextFrame y sus propiedades
    shape.TextFrame.Text = "3D Text";
	// Configurar FillFormat.FillType como FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// Configurar porción de TextFrame y configurar propiedades de PortionFormat
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // configurar efecto de transformación "Arch Up" de WordArt
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// Definir propiedades de ThreeDFormat de ITextFrame
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Guardar el archivo de la presentación
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### Ver También

* class [PVIObject](../pviobject)
* interface [IThreeDFormat](../ithreedformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->