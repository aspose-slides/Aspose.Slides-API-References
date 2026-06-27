---
title: ThreeDFormat
second_title: Aspose.Sildes για .NET API Αναφορά
description: Αναπαριστά τις ιδιότητες 3-Δ.
type: docs
weight: 11470
url: /el/aspose.slides/threedformat/
---
## ThreeDFormat κλάση

Αναπαριστά τις ιδιότητες 3-Δ.

```csharp
public sealed class ThreeDFormat : PVIObject, IThreeDFormat
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Επιτρέπει την πρόσβαση στη βασική διεπαφή IPresentationComponent. Μόνο για ανάγνωση [`IPresentationComponent`](../ipresentationcomponent). |
| [BevelBottom](../../aspose.slides/threedformat/bevelbottom) { get; } | Επιστρέφει ή ορίζει τον τύπο της κάτω 3Δ ανάπλεξης. Μόνο για ανάγνωση [`IShapeBevel`](../ishapebevel). |
| [BevelTop](../../aspose.slides/threedformat/beveltop) { get; } | Επιστρέφει ή ορίζει τον τύπο της άνω 3Δ ανάπλεξης. Μόνο για ανάγνωση [`IShapeBevel`](../ishapebevel). |
| [Camera](../../aspose.slides/threedformat/camera) { get; } | Επιστρέφει ή ορίζει τις ρυθμίσεις μιας κάμερας. Μόνο για ανάγνωση [`ICamera`](../icamera). |
| [ContourColor](../../aspose.slides/threedformat/contourcolor) { get; } | Επιστρέφει ή ορίζει το χρώμα ενός περιγράμματος. Μόνο για ανάγνωση [`IColorFormat`](../icolorformat). |
| [ContourWidth](../../aspose.slides/threedformat/contourwidth) { get; set; } | Επιστρέφει ή ορίζει το πλάτος ενός 3Δ περιγράμματος. Ανάγνωση/Εγγραφή Double. |
| [Depth](../../aspose.slides/threedformat/depth) { get; set; } | Επιστρέφει ή ορίζει το βάθος ενός 3Δ σχήματος. Ανάγνωση/Εγγραφή Double. |
| [ExtrusionColor](../../aspose.slides/threedformat/extrusioncolor) { get; } | Επιστρέφει ή ορίζει το χρώμα μιας εξώθησης. Μόνο για ανάγνωση [`IColorFormat`](../icolorformat). |
| [ExtrusionHeight](../../aspose.slides/threedformat/extrusionheight) { get; set; } | Επιστρέφει ή ορίζει το ύψος ενός εφέ εξώθησης. Ανάγνωση/Εγγραφή Double. |
| [LightRig](../../aspose.slides/threedformat/lightrig) { get; } | Επιστρέφει ή ορίζει τον τύπο ενός φωτός. Μόνο για ανάγνωση [`ILightRig`](../ilightrig). |
| [Material](../../aspose.slides/threedformat/material) { get; set; } | Επιστρέφει ή ορίζει τον τύπο ενός υλικού. Ανάγνωση/Εγγραφή [`MaterialPresetType`](../materialpresettype). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Συγκρίνει με το καθορισμένο αντικείμενο. |
| [GetEffective](../../aspose.slides/threedformat/geteffective)() | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης 3-Δ με την εφαρμογή κληρονομικότητας. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Επιστρέφει τον κώδικα κατακερματισμού. |

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ένα 3Δ σχήμα σε παρουσίαση PowerPoint.

```csharp
[C#]
// Δημιουργήστε ένα στιγμιότυπο της κλάσης Presentation.
using (Presentation pres = new Presentation())
{
	// Προσθέστε ένα σχήμα χρησιμοποιώντας τη μέθοδο AddAutoShape method
    IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 200, 200);
	// Ορίστε το TextFrame και τις ιδιότητές του
    shape.TextFrame.Text = "3D";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Ορίστε τις ιδιότητες ThreeDFormat Properties
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Αποθηκεύστε το αρχείο Presentation file
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Το παρακάτω παράδειγμα δείχνει πώς να εφαρμόσετε το εφέ διαβάθμισης σε 3Δ σχήμα σε παρουσίαση PowerPoint.

```csharp
[C#]
// Δημιουργήστε ένα στιγμιότυπο της κλάσης Presentation.
using (Presentation pres = new Presentation())
{
	// Προσθέστε ένα σχήμα χρησιμοποιώντας τη μέθοδο AddAutoShape method
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Ορίστε το TextFrame και τις ιδιότητές του
    shape.TextFrame.Text = "3D Gradient";
    shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 64;
	// Διαμορφώστε το FillFormat.FillType ως FillType.Gradient και ορίστε τις ιδιότητες διαβάθμισης
	shape.FillFormat.FillType = FillType.Gradient;
    shape.FillFormat.GradientFormat.GradientStops.Add(0, Color.Blue);
    shape.FillFormat.GradientFormat.GradientStops.Add(100, Color.Orange);
	// Ορίστε τις ιδιότητες ThreeDFormat Properties
    shape.ThreeDFormat.Camera.CameraType = CameraPresetType.OrthographicFront;
    shape.ThreeDFormat.Camera.SetRotation(20, 30, 40);
    shape.ThreeDFormat.LightRig.LightType = LightRigPresetType.Flat;
    shape.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    shape.ThreeDFormat.Material = MaterialPresetType.Flat;
    shape.ThreeDFormat.ExtrusionHeight = 100;
    shape.ThreeDFormat.ExtrusionColor.Color = Color.Blue;
    pres.Slides[0].GetThumbnail(2, 2).Save("sample_3d.png");
	// Αποθηκεύστε το αρχείο Presentation file
    pres.Save("sandbox_3d.pptx", SaveFormat.Pptx);
}
```

Το παρακάτω παράδειγμα δείχνει πώς να εφαρμόσετε εφέ 3Δ σε κείμενο. Για τη δημιουργία 3Δ κειμένου είναι δυνατό να χρησιμοποιήσετε το εφέ μετασχηματισμού WordArt.

```csharp
[C#]
// Δημιουργήστε ένα στιγμιότυπο της κλάσης Presentation.
using (Presentation pres = new Presentation())
{
	// Προσθέστε ένα σχήμα χρησιμοποιώντας τη μέθοδο AddAutoShape method
     IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 150, 250, 250);
	// Ορίστε το TextFrame και τις ιδιότητές του
    shape.TextFrame.Text = "3D Text";
	// Διαμορφώστε το FillFormat.FillType ως FillType.NoFill
	shape.FillFormat.FillType = FillType.NoFill;
    shape.LineFormat.FillFormat.FillType = FillType.NoFill;
	// Διαμορφώστε το Portion του TextFrame και τις ιδιότητες του PortionFormat
	Portion portion = (Portion)shape.TextFrame.Paragraphs[0].Portions[0];
    portion.PortionFormat.FillFormat.FillType = FillType.Pattern;
    portion.PortionFormat.FillFormat.PatternFormat.ForeColor.Color = Color.DarkOrange;
    portion.PortionFormat.FillFormat.PatternFormat.BackColor.Color = Color.White;
    portion.PortionFormat.FillFormat.PatternFormat.PatternStyle = PatternStyle.LargeGrid;
	shape.TextFrame.Paragraphs[0].ParagraphFormat.DefaultPortionFormat.FontHeight = 128;
    ITextFrame textFrame = shape.TextFrame;
    // Ρυθμίστε το εφέ μετασχηματισμού WordArt "Arch Up"
    textFrame.TextFrameFormat.Transform = TextShapeType.ArchUp;
	// Ορίστε τις ιδιότητες ThreeDFormat του ITextFrame
	textFrame.TextFrameFormat.ThreeDFormat.ExtrusionHeight = 3.5f;
    textFrame.TextFrameFormat.ThreeDFormat.Depth = 3;
    textFrame.TextFrameFormat.ThreeDFormat.Material = MaterialPresetType.Plastic;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.Direction = LightingDirection.Top;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.LightType = LightRigPresetType.Balanced;
    textFrame.TextFrameFormat.ThreeDFormat.LightRig.SetRotation(0, 0, 40);
    textFrame.TextFrameFormat.ThreeDFormat.Camera.CameraType = CameraPresetType.PerspectiveContrastingRightFacing;
    pres.Slides[0].GetThumbnail(2, 2).Save("text3d.png");
	// Αποθηκεύστε το αρχείο Presentation file
     pres.Save("text3d.pptx", SaveFormat.Pptx);
}
```

### Δείτε επίσης

* κλάση [PVIObject](../pviobject)
* διασύνδεση [IThreeDFormat](../ithreedformat)
* χώρο ονομάτων [Aspose.Slides](../../aspose.slides)
* συγκρότημα [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->