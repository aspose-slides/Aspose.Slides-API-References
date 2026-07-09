---
title: ThreeDFormat
second_title: Aspose.Sildes dla .NET - Dokumentacja API
description: Reprezentuje własności 3-D.
type: docs
weight: 11490
url: /pl/aspose.slides/threedformat/
---
## ThreeDFormat klasa

Reprezentuje własności 3-D.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## Właściwości

| Nazwa | Opis |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umożliwia pobranie podstawowego interfejsu IPresentationComponent. Tylko do odczytu [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | Zwraca lub ustawia typ dolnego 3D bevel. Tylko do odczytu [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | Zwraca lub ustawia typ górnego 3D bevel. Tylko do odczytu [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | Zwraca lub ustawia ustawienia kamery. Tylko do odczytu [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | Zwraca lub ustawia kolor konturu. Tylko do odczytu [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | Zwraca lub ustawia szerokość konturu 3D. Odczyt/zapis Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | Zwraca lub ustawia głębokość kształtu 3D. Odczyt/zapis Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | Zwraca lub ustawia kolor ekstruzji. Tylko do odczytu [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | Zwraca lub ustawia wysokość efektu ekstruzji. Odczyt/zapis Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | Zwraca lub ustawia typ światła. Tylko do odczytu [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | Zwraca lub ustawia typ materiału. Odczyt/zapis [`MaterialPresetType`](../materialpresettype). |

## Metody

| Nazwa | Opis |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porównuje z określonym obiektem. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | Pobiera efektywne dane formatowania 3D z zastosowanym dziedziczeniem. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Zwraca kod hash. |

### Przykłady

Poniższy przykład pokazuje, jak dodać kształt 3D w prezentacji PowerPoint.

```csharp
[C#]
// Utwórz instancję klasy Presentation.
using (Presentation pres = new Presentation())
{
	// Dodaj kształt używając metody AddAutoShape
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// Zdefiniuj TextFrame i jego właściwości
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Zdefiniuj właściwości ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Zapisz plik prezentacji
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Poniższy przykład pokazuje, jak zastosować efekt gradientu do kształtu 3D w prezentacji PowerPoint.

```csharp
[C#]
// Utwórz instancję klasy Presentation.
using (Presentation pres = new Presentation())
{
	// Dodaj kształt używając metody AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Zdefiniuj TextFrame i jego właściwości
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Skonfiguruj FillFormat.FillType jako FillType.Gradient i zdefiniuj właściwości gradientu
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// Zdefiniuj właściwości ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Zapisz plik prezentacji
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Poniższy przykład pokazuje, jak zastosować efekt 3D na tekście. Do stworzenia tekstu 3D można użyć efektu transformacji WordArt.

```csharp
[C#]
// Utwórz instancję klasy Presentation.
using (Presentation pres = new Presentation())
{
	// Dodaj kształt używając metody AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Zdefiniuj TextFrame i jego właściwości
    shape.TextFrame.Text = "3D Text";
	// Skonfiguruj FillFormat.FillType jako FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// Skonfiguruj porcję TextFrame i właściwości PortionFormat
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // Ustaw efekt transformacji WordArt "Arch Up"
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// Zdefiniuj właściwości ThreeDFormat dla ITextFrame
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Zapisz plik prezentacji
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### Zobacz także

* klasa [PVIObject](../pviobject)
* interfejs [IThreeDFormat](../ithreedformat)
* przestrzeń nazw [Aspose.Slides](../../aspose.slides)
* zestaw [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->