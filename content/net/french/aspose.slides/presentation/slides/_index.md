---
title: Slides
second_title: Aspose.Slides pour .NET API Reference
description: Renvoie une liste de toutes les diapositives définies dans la présentation. Lecture seule ISlideCollectionaspose.slides/islidecollection.
type: docs
weight: 230
url: /fr/aspose.slides/presentation/slides/
---

## Propriété Presentation.Slides

Renvoie une liste de toutes les diapositives définies dans la présentation. Lecture seule [`ISlideCollection`](../../islidecollection).

```csharp
public ISlideCollection Slides { get; }
```

### Exemples

L'exemple suivant montre comment définir la couleur de fond des diapositives d'une présentation PowerPoint.

```csharp
[C#]
// Instancier la classe Presentation qui représente le fichier de présentation
using (Presentation pres = new Presentation())
{
    // Définir la couleur de fond de la première ISlide en bleu
    pres.Slides[0].Background.Type = BackgroundType.OwnBackground;
    pres.Slides[0].Background.FillFormat.FillType = FillType.Solid;
    pres.Slides[0].Background.FillFormat.SolidFillColor.Color = Color.Blue;
    pres.Save("ContentBG_out.pptx", SaveFormat.Pptx);
}
```

L'exemple suivant montre comment définir l'image de fond des diapositives d'une présentation PowerPoint.

```csharp
[C#]
// Instancier la classe Presentation qui représente le fichier de présentation
using (Presentation pres = new Presentation("SetImageAsBackground.pptx"))
{
    // Définir le fond avec une image
    pres.Slides[0].Background.Type = BackgroundType.OwnBackground;
    pres.Slides[0].Background.FillFormat.FillType = FillType.Picture;
    pres.Slides[0].Background.FillFormat.PictureFillFormat.PictureFillMode = PictureFillMode.Stretch;
    // Définir l'image
    System.Drawing.Image img = (System.Drawing.Image)new Bitmap(dataDir + "Tulips.jpg");
    // Ajouter l'image à la collection d'images de la présentation
    IPPImage imgx = pres.Images.AddImage(img);
    pres.Slides[0].Background.FillFormat.PictureFillFormat.Picture.Image = imgx;
    // Écrire la présentation sur le disque
    pres.Save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
}
```

L'exemple suivant montre comment ajouter une transition de diapositive dans une présentation.

```csharp
[C#]
// Instancier la classe Presentation pour charger le fichier de présentation source
using (Presentation presentation = new Presentation("AccessSlides.pptx"))
{
    // Appliquer une transition de type cercle sur la diapositive 1
    presentation.Slides[0].SlideShowTransition.Type = TransitionType.Circle;
    // Appliquer une transition de type combinaison sur la diapositive 2
    presentation.Slides[1].SlideShowTransition.Type = TransitionType.Comb;
    // Écrire la présentation sur le disque
    presentation.Save("SampleTransition_out.pptx", SaveFormat.Pptx);
}
```

L'exemple suivant montre comment ajouter une transition de diapositive avancée.

```csharp
[C#]
// Instancier la classe Presentation qui représente un fichier de présentation
using (Presentation pres = new Presentation("BetterSlideTransitions.pptx"))
{
    // Appliquer une transition de type cercle sur la diapositive 1
    pres.Slides[0].SlideShowTransition.Type = TransitionType.Circle;
    // Définir le temps de transition à 3 secondes
    pres.Slides[0].SlideShowTransition.AdvanceOnClick = true;
    pres.Slides[0].SlideShowTransition.AdvanceAfterTime = 3000;
    // Appliquer une transition de type combinaison sur la diapositive 2
    pres.Slides[1].SlideShowTransition.Type = TransitionType.Comb;
    // Définir le temps de transition à 5 secondes
    pres.Slides[1].SlideShowTransition.AdvanceOnClick = true;
    pres.Slides[1].SlideShowTransition.AdvanceAfterTime = 5000;
    // Appliquer une transition de type zoom sur la diapositive 3
    pres.Slides[2].SlideShowTransition.Type = TransitionType.Zoom;
    // Définir le temps de transition à 7 secondes
    pres.Slides[2].SlideShowTransition.AdvanceOnClick = true;
    pres.Slides[2].SlideShowTransition.AdvanceAfterTime = 7000;
    // Écrire la présentation sur le disque
    pres.Save("SampleTransition_out.pptx", SaveFormat.Pptx);
}
```

### Voir aussi

* interface [ISlideCollection](../../islidecollection)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->