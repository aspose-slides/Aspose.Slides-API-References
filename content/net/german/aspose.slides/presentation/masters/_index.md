---
title: Masters
second_title: Aspose.Sildes für .NET API-Referenz
description: Gibt eine Liste aller Master-Folien zurück, die in der Präsentation definiert sind. Nur-Lese IMasterSlideCollectionaspose.slides/imasterslidecollection.
type: docs
weight: 180
url: /de/aspose.slides/presentation/masters/
---

## Presentation.Masters-Eigenschaft

Gibt eine Liste aller Master-Folien zurück, die in der Präsentation definiert sind. Nur-Lese [`IMasterSlideCollection`](../../imasterslidecollection).

```csharp
public IMasterSlideCollection Masters { get; }
```

### Beispiele

Die folgenden Beispiele zeigen, wie man Bilder zu Master-Folien einer PowerPoint-Präsentation hinzufügt.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide slide = pres.Slides[0];
    IMasterSlide masterSlide = slide.LayoutSlide.MasterSlide;
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.png"));
    masterSlide.Shapes.AddPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    pres.Save("pres.pptx", SaveFormat.Pptx);
}
```

Die folgenden Beispiele zeigen, wie man die Hintergrundfarbe der Master-Folie einer PowerPoint-Präsentation ändert.

```csharp
[C#]
// Instanziieren der Presentation-Klasse, die die Präsentationsdatei darstellt
using (Presentation pres = new Presentation())
{
    // Setzen der Hintergrundfarbe der Master ISlide auf Waldgrün
    pres.Masters[0].Background.Type = BackgroundType.OwnBackground;
    pres.Masters[0].Background.FillFormat.FillType = FillType.Solid;
    pres.Masters[0].Background.FillFormat.SolidFillColor.Color = Color.ForestGreen;
    // Schreiben der Präsentation auf die Festplatte
    pres.Save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
}
```

Die folgenden Beispiele zeigen, wie man eine Folienlayout zu einer PowerPoint-Präsentation hinzufügt.

```csharp
[C#]
// Instanziieren der Presentation-Klasse, die die Präsentationsdatei darstellt
using (Presentation presentation = new Presentation("AccessSlides.pptx"))
{
    // Versuchen, nach Folienlayouttyp zu suchen
    IMasterLayoutSlideCollection layoutSlides = presentation.Masters[0].LayoutSlides;
    ILayoutSlide layoutSlide = layoutSlides.GetByType(SlideLayoutType.TitleAndObject) ?? layoutSlides.GetByType(SlideLayoutType.Title);
    if (layoutSlide == null)
    {
        // Die Situation, wenn eine Präsentation einige Layouttypen nicht enthält.
        // Die Präsentationsdatei enthält nur leere und benutzerdefinierte Layouttypen.
        // Aber Layout-Folien mit benutzerdefinierten Typen haben unterschiedliche Foliennamen,
        // wie "Titel", "Titel und Inhalt" usw. Und es ist möglich, diese
        // Namen zur Auswahl von Layoutfolien zu verwenden.
        // Es ist auch möglich, eine Gruppe von Platzhalter-Folienformen zu verwenden. Zum Beispiel,
        // sollte die Titelfolie nur den Platzhalter-Typ Titel haben, usw.
        foreach (ILayoutSlide titleAndObjectLayoutSlide in layoutSlides)
        {
            if (titleAndObjectLayoutSlide.Name == "Titel und Objekt")
            {
                layoutSlide = titleAndObjectLayoutSlide;
                break;
            }
        }
        if (layoutSlide == null)
        {
            foreach (ILayoutSlide titleLayoutSlide in layoutSlides)
            {
                if (titleLayoutSlide.Name == "Titel")
                {
                    layoutSlide = titleLayoutSlide;
                    break;
                }
            }
            if (layoutSlide == null)
            {
                layoutSlide = layoutSlides.GetByType(SlideLayoutType.Blank);
                if (layoutSlide == null)
                {
                    layoutSlide = layoutSlides.Add(SlideLayoutType.TitleAndObject, "Titel und Objekt");
                }
            }
        }
    }
    // Leere Folie mit hinzugefügtem Layout-Layout hinzufügen
    presentation.Slides.InsertEmptySlide(0, layoutSlide);
    // Präsentation speichern
    presentation.Save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
}
```

### Siehe auch

* Schnittstelle [IMasterSlideCollection](../../imasterslidecollection)
* Klasse [Presentation](../../presentation)
* Namensraum [Aspose.Slides](../../presentation)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->