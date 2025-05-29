---
title: Folien
second_title: Aspose.Slides für .NET API Referenz
description: Gibt eine Liste aller Folien zurück, die in der Präsentation definiert sind. Nur-lesbare ISlideCollectionaspose.slides/islidecollection.
type: docs
weight: 230
url: /de/aspose.slides/presentation/slides/
---

## Presentation.Slides-Eigenschaft

Gibt eine Liste aller Folien zurück, die in der Präsentation definiert sind. Nur-lesbare [`ISlideCollection`](../../islidecollection).

```csharp
public ISlideCollection Slides { get; }
```

### Beispiele

Das folgende Beispiel zeigt, wie man die Hintergrundfarbe von Folien in einer PowerPoint-Präsentation gesetzt.

```csharp
[C#]
// Instanziiere die Presentation-Klasse, die die Präsentationsdatei darstellt
using (Presentation pres = new Presentation())
{
    // Setze die Hintergrundfarbe der ersten ISlide auf Blau
    pres.Slides[0].Background.Type = BackgroundType.OwnBackground;
    pres.Slides[0].Background.FillFormat.FillType = FillType.Solid;
    pres.Slides[0].Background.FillFormat.SolidFillColor.Color = Color.Blue;
    pres.Save("ContentBG_out.pptx", SaveFormat.Pptx);
}
```

Das folgende Beispiel zeigt, wie man das Hintergrundbild von Folien in einer PowerPoint-Präsentation gesetzt.

```csharp
[C#]
// Instanziiere die Presentation-Klasse, die die Präsentationsdatei darstellt
using (Presentation pres = new Presentation("SetImageAsBackground.pptx"))
{
    // Setze den Hintergrund mit einem Bild
    pres.Slides[0].Background.Type = BackgroundType.OwnBackground;
    pres.Slides[0].Background.FillFormat.FillType = FillType.Picture;
    pres.Slides[0].Background.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;
    // Setze das Bild
    System.Drawing.Image img = (System.Drawing.Image)new Bitmap(dataDir + "Tulips.jpg");
    // Füge das Bild zur Bildersammlung der Präsentation hinzu
    IPPImage imgx = pres.Images.AddImage(img);
    pres.Slides[0].Background.FillFormat.PictureFillFormat.Picture.Image = imgx;
    // Schreibe die Präsentation auf die Festplatte
    pres.Save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
}
```

Das folgende Beispiel zeigt, wie man Folienübergänge in der Präsentation hinzufügt.

```csharp
[C#]
// Instanziiere die Presentation-Klasse, um die Quelldatei der Präsentation zu laden
using (Presentation presentation = new Presentation("AccessSlides.pptx"))
{
    // Wende den Übergangstyp Kreis auf Folie 1 an
    presentation.Slides[0].SlideShowTransition.Type = TransitionType.Circle;
    // Wende den Übergangstyp Kombi auf Folie 2 an
    presentation.Slides[1].SlideShowTransition.Type = TransitionType.Comb;
    // Schreibe die Präsentation auf die Festplatte
    presentation.Save("SampleTransition_out.pptx", SaveFormat.Pptx);
}
```

Das folgende Beispiel zeigt, wie man erweiterte Folienübergänge hinzufügt.

```csharp
[C#]
// Instanziiere die Presentation-Klasse, die eine Präsentationsdatei darstellt
using (Presentation pres = new Presentation("BetterSlideTransitions.pptx"))
{
    // Wende den Übergangstyp Kreis auf Folie 1 an
    pres.Slides[0].SlideShowTransition.Type = TransitionType.Circle;
    // Setze die Übergangszeit auf 3 Sekunden
    pres.Slides[0].SlideShowTransition.AdvanceOnClick = true;
    pres.Slides[0].SlideShowTransition.AdvanceAfterTime = 3000;
    // Wende den Übergangstyp Kombi auf Folie 2 an
    pres.Slides[1].SlideShowTransition.Type = TransitionType.Comb;
    // Setze die Übergangszeit auf 5 Sekunden
    pres.Slides[1].SlideShowTransition.AdvanceOnClick = true;
    pres.Slides[1].SlideShowTransition.AdvanceAfterTime = 5000;
    // Wende den Übergangstyp Zoom auf Folie 3 an
    pres.Slides[2].SlideShowTransition.Type = TransitionType.Zoom;
    // Setze die Übergangszeit auf 7 Sekunden
    pres.Slides[2].SlideShowTransition.AdvanceOnClick = true;
    pres.Slides[2].SlideShowTransition.AdvanceAfterTime = 7000;
    // Schreibe die Präsentation auf die Festplatte
    pres.Save("SampleTransition_out.pptx", SaveFormat.Pptx);
}
```

### Siehe Auch

* interface [ISlideCollection](../../islidecollection)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->