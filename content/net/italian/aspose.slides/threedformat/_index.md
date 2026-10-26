---
title: ThreeDFormat
second_title: Aspose.Sildes per .NET - Riferimento API
description: Rappresenta le proprietà 3-D.
type: docs
weight: 11490
url: /it/aspose.slides/threedformat/
---
## ThreeDFormat classe

Rappresenta le proprietà 3-D.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Consente di ottenere l'interfaccia base IPresentationComponent. Solo lettura [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | Restituisce o imposta il tipo di una smussatura 3D inferiore. Solo lettura [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | Restituisce o imposta il tipo di una smussatura 3D superiore. Solo lettura [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | Restituisce o imposta le impostazioni di una fotocamera. Solo lettura [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | Restituisce o imposta il colore di un contorno. Solo lettura [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | Restituisce o imposta la larghezza di un contorno 3D. Lettura/scrittura Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | Restituisce o imposta la profondità di una forma 3D. Lettura/scrittura Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | Restituisce o imposta il colore di un'estrusione. Solo lettura [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | Restituisce o imposta l'altezza di un effetto di estrusione. Lettura/scrittura Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | Restituisce o imposta il tipo di una luce. Solo lettura [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | Restituisce o imposta il tipo di un materiale. Lettura/scrittura [`MaterialPresetType`](../materialpresettype). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Confronta con l'oggetto specificato. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | Ottiene i dati di formattazione 3-D effettivi con l'ereditarietà applicata. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Restituisce il codice hash. |

### Esempi

Il seguente esempio mostra come aggiungere una forma 3D in una presentazione PowerPoint.

```csharp
[C#]
// Crea un'istanza della classe Presentation.
using (Presentation pres = new Presentation())
{
	// Aggiungi una forma usando il metodo AddAutoShape
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// Definisci TextFrame e le sue proprietà
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Definisci le proprietà di ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Salva il file Presentation
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Il seguente esempio mostra come applicare l'effetto gradiente a una forma 3D in una presentazione PowerPoint.

```csharp
[C#]
// Crea un'istanza della classe Presentation.
using (Presentation pres = new Presentation())
{
	// Aggiungi una forma usando il metodo AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Definisci TextFrame e le sue proprietà
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Configura FillFormat.FillType come FillType.Gradient e definisci le proprietà del gradiente
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// Definisci le proprietà di ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Salva il file Presentation
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Il seguente esempio mostra come applicare l'effetto 3D al testo. Per creare un testo 3D è possibile utilizzare l'effetto di trasformazione WordArt.

```csharp
[C#]
// Crea un'istanza della classe Presentation.
using (Presentation pres = new Presentation())
{
	// Aggiungi una forma usando il metodo AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Definisci TextFrame e le sue proprietà
    shape.TextFrame.Text = "3D Text";
	// Configura FillFormat.FillType come FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// Configura la Porzione di TextFrame e le proprietà di PortionFormat
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // imposta l'effetto di trasformazione WordArt "Arch Up"
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// Definisci le proprietà di ThreeDFormat di ITextFrame
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Salva il file Presentation
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### Vedi anche

* classe [PVIObject](../pviobject)
* interfaccia [IThreeDFormat](../ithreedformat)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->