---
title: ThreeDFormat
second_title: Aspose.Sildes para .NET Referência da API
description: Representa propriedades 3-D.
type: docs
weight: 11490
url: /pt/aspose.slides/threedformat/
---
## ThreeDFormat classe

Representa propriedades 3-D.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obter a interface base IPresentationComponent. Somente leitura [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | Retorna ou define o tipo de um chanfro 3D inferior. Somente leitura [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | Retorna ou define o tipo de um chanfro 3D superior. Somente leitura [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | Retorna ou define as configurações de uma câmera. Somente leitura [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | Retorna ou define a cor de um contorno. Somente leitura [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | Retorna ou define a largura de um contorno 3D. Leitura/gravação Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | Retorna ou define a profundidade de uma forma 3D. Leitura/gravação Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | Retorna ou define a cor de uma extrusão. Somente leitura [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | Retorna ou define a altura de um efeito de extrusão. Leitura/gravação Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | Retorna ou define o tipo de uma luz. Somente leitura [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | Retorna ou define o tipo de um material. Leitura/gravação [`MaterialPresetType`](../materialpresettype). |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compara com o objeto especificado. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | Obtém os dados de formatação 3-D efetivos com a herança aplicada. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retorna o código hash. |

### Exemplos

O exemplo a seguir mostra como adicionar uma forma 3D em uma Apresentação do PowerPoint.

```csharp
[C#]
// Crie uma instância da classe Presentation.
using (Presentation pres = new Presentation())
{
	// Adicione uma forma usando o método AddAutoShape
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// Defina TextFrame e suas propriedades
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Defina as propriedades de ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Salve o arquivo Presentation
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

O exemplo a seguir mostra como aplicar efeito de gradiente a uma forma 3D em uma Apresentação do PowerPoint.

```csharp
[C#]
// Crie uma instância da classe Presentation.
using (Presentation pres = new Presentation())
{
	// Adicione uma forma usando o método AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Defina TextFrame e suas propriedades
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Configure FillFormat.FillType como FillType.Gradient e defina as propriedades do gradiente
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// Defina as propriedades de ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Salve o arquivo Presentation
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

O exemplo a seguir mostra como aplicar efeito 3D em texto. Para criar um texto 3D é possível usar o efeito de transformação WordArt.

```csharp
[C#]
// Crie uma instância da classe Presentation.
using (Presentation pres = new Presentation())
{
	// Adicione uma forma usando o método AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Defina TextFrame e suas propriedades
    shape.TextFrame.Text = "3D Text";
	// Configure FillFormat.FillType como FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// Configure Porção de TextFrame e configure as propriedades de PortionFormat
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // configure o efeito de transformação WordArt "Arch Up"
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// Defina as propriedades de ThreeDFormat de ITextFrame
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Salve o arquivo Presentation
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### Veja Também

* classe [PVIObject](../pviobject)
* interface [IThreeDFormat](../ithreedformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->