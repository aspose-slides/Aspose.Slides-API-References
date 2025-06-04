---
title: ThreeDFormat
second_title: Aspose.Sildes pour .NET API Référence
description: Représente les propriétés 3-D.
type: docs
weight: 11180
url: /fr/aspose.slides/threedformat/
---

## ThreeDFormat class

Représente les propriétés 3-D.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permet d'obtenir l'interface IPresentationComponent de base. En lecture seule [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | Retourne ou définit le type d'un biseau 3D inférieur. En lecture seule [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | Retourne ou définit le type d'un biseau 3D supérieur. En lecture seule [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | Retourne ou définit les paramètres d'une caméra. En lecture seule [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | Retourne ou définit la couleur d'un contour. En lecture seule [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | Retourne ou définit la largeur d'un contour 3D. En lecture/écriture Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | Retourne ou définit la profondeur d'une forme 3D. En lecture/écriture Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | Retourne ou définit la couleur d'une extrusion. En lecture seule [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | Retourne ou définit la hauteur d'un effet d'extrusion. En lecture/écriture Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | Retourne ou définit le type d'une lumière. En lecture seule [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | Retourne ou définit le type d'un matériau. En lecture/écriture [`MaterialPresetType`](../materialpresettype). |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Compare avec l'objet spécifié. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | Obtient les données de formatage 3D effectives avec l'héritage appliqué. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retourne le code de hachage. |

### Exemples

L'exemple suivant montre comment ajouter une forme 3D dans une présentation PowerPoint.

```csharp
[C#]
// Créer une instance de la classe Presentation.
using (Presentation pres = new Presentation())
{
	// Ajouter une forme en utilisant la méthode AddAutoShape
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// Définir le TextFrame et ses propriétés
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Définir les propriétés de ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Enregistrer le fichier de présentation
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

L'exemple suivant montre comment appliquer un effet de dégradé à une forme 3D dans une présentation PowerPoint.

```csharp
[C#]
// Créer une instance de la classe Presentation.
using (Presentation pres = new Presentation())
{
	// Ajouter une forme en utilisant la méthode AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Définir le TextFrame et ses propriétés
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Configurer FillFormat.FillType comme FillType.Gradient et définir les propriétés du dégradé
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// Définir les propriétés de ThreeDFormat
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Enregistrer le fichier de présentation
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

L'exemple suivant montre comment appliquer un effet 3D sur du texte. Pour créer un texte 3D, il est possible d'utiliser l'effet de transformation WordArt.

```csharp
[C#]
// Créer une instance de la classe Presentation.
using (Presentation pres = new Presentation())
{
	// Ajouter une forme en utilisant la méthode AddAutoShape
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Définir le TextFrame et ses propriétés
    shape.TextFrame.Text = "3D Text";
	// Configurer FillFormat.FillType comme FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// Configurer la portion de TextFrame et configurer les propriétés de PortionFormat
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // configurer l'effet de transformation WordArt "Arch Up"
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// Définir les propriétés de ThreeDFormat de ITextFrame
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Enregistrer le fichier de présentation
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### Voir aussi

* class [PVIObject](../pviobject)
* interface [IThreeDFormat](../ithreedformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->