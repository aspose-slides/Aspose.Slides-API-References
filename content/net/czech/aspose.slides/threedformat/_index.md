---
title: ThreeDFormat
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje 3-D vlastnosti.
type: docs
weight: 11490
url: /cs/aspose.slides/threedformat/
---
## ThreeDFormat třída

Represents 3-D properties.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umožňuje získat základní rozhraní IPresentationComponent. Pouze pro čtení [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | Vrací nebo nastavuje typ spodního 3D zkosení. Pouze pro čtení [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | Vrací nebo nastavuje typ horního 3D zkosení. Pouze pro čtení [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | Vrací nebo nastavuje nastavení kamery. Pouze pro čtení [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | Vrací nebo nastavuje barvu kontury. Pouze pro čtení [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | Vrací nebo nastavuje šířku 3D kontury. Čtení/zápis Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | Vrací nebo nastavuje hloubku 3D tvaru. Čtení/zápis Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | Vrací nebo nastavuje barvu extruze. Pouze pro čtení [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | Vrací nebo nastavuje výšku efektu extruze. Čtení/zápis Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | Vrací nebo nastavuje typ světla. Pouze pro čtení [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | Vrací nebo nastavuje typ materiálu. Čtení/zápis [`MaterialPresetType`](../materialpresettype). |

## Metody

| Název | Popis |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porovnává se se zadaným objektem. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | Získává efektivní 3-D formátovací data s použitím dědičnosti. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Vrací hash kód. |

### Příklady

Následující příklad ukazuje, jak přidat 3D tvar do prezentace PowerPoint.

```csharp
[C#]
// Vytvořte instanci třídy Presentation.
using (Presentation pres = new Presentation())
{
	// Přidejte tvar pomocí metody AddAutoShape
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// Definujte TextFrame a jeho vlastnosti
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Definujte vlastnosti ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Uložte soubor prezentace
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Následující příklad ukazuje, jak použít gradientní efekt na 3D tvar v prezentaci PowerPoint.

```csharp
[C#]
// Vytvořte instanci třídy Presentation.
using (Presentation pres = new Presentation())
{
	// Přidejte tvar pomocí metody AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Definujte TextFrame a jeho vlastnosti
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Nastavte FillFormat.FillType na FillType.Gradient a definujte vlastnosti gradientu
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// Definujte vlastnosti ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Uložte soubor prezentace
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Následující příklad ukazuje, jak aplikovat 3D efekt na text. Pro vytvoření 3D textu lze použít efekt transformace WordArt.

```csharp
[C#]
// Vytvořte instanci třídy Presentation.
using (Presentation pres = new Presentation())
{
	// Přidejte tvar pomocí metody AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Definujte TextFrame a jeho vlastnosti
    shape.TextFrame.Text = "3D Text";
	// Nastavte FillFormat.FillType jako FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// Nastavte Portion TextFrame a upravte vlastnosti PortionFormat
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // nastavení transformace WordArt „Arch Up“
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// Definujte vlastnosti ThreeDFormat pro ITextFrame
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Uložte soubor prezentace
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### Viz také

* třída [PVIObject](../pviobject)
* rozhraní [IThreeDFormat](../ithreedformat)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->