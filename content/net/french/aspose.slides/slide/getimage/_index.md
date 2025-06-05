---
title: GetImage
second_title: Aspose.Sildes pour la référence API .NET
description: Renvoie un objet Image Thumbnail avec un scaling personnalisé.
type: docs
weight: 80
url: /fr/aspose.slides/slide/getimage/
---

## GetImage(float, float) {#getimage_5}

Renvoie un objet Image Thumbnail avec un scaling personnalisé.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| scaleX | Single | La valeur par laquelle scalier ce Thumbnail dans la direction de l'axe x. |
| scaleY | Single | La valeur par laquelle scalier ce Thumbnail dans la direction de l'axe y. |

### Valeur de retour

Objet IImage.

### Exemples

L'exemple suivant montre comment générer des vignettes à partir d'une présentation PowerPoint.

```csharp
[C#]
// Instancier une classe Presentation qui représente le fichier de présentation
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // Accéder à la première diapositive
    ISlide sld = pres.Slides[0];
    // Créer une image à pleine échelle
    IImage bmp = sld.GetImage(1f, 1f);
    // Enregistrer l'image sur disque au format JPEG
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

L'exemple suivant montre comment convertir des diapositives en bitmap et enregistrer les images en PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Convertit la première diapositive de la présentation en un objet Bitmap
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // Enregistre l'image au format PNG
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

L'exemple suivant montre comment convertir PowerPoint PPT/PPTX en JPG.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// Créer une image à pleine échelle
		IImage bmp = sld.GetImage(1f, 1f);
		// Enregistrer l'image sur disque au format JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

L'exemple suivant montre comment convertir PowerPoint PPT/PPTX en JPG avec des dimensions personnalisées.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// Définir les dimensions
	int desiredX = 1200;
	int desiredY = 800;
	// Obtenir les valeurs mises à l'échelle de X et Y
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// Créer une image à pleine échelle
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// Enregistrer l'image sur disque au format JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### Voir Aussi

* interface [IImage](../../iimage)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

Renvoie un objet Image Thumbnail (20 % de la taille réelle).

```csharp
public IImage GetImage()
```

### Voir Aussi

* interface [IImage](../../iimage)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

Renvoie un objet Image Thumbnail avec une taille spécifiée.

```csharp
public IImage GetImage(Size imageSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| imageSize | Size | Taille de l'image à créer. |

### Valeur de retour

Objet Image.

### Exemples

L'exemple suivant montre comment convertir des diapositives en images avec des tailles personnalisées en utilisant C#.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Convertit la première diapositive de la présentation en un Bitmap avec la taille spécifiée
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // Enregistre l'image au format JPEG
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### Voir Aussi

* interface [IImage](../../iimage)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

Renvoie un objet image tiff Thumbnail avec des paramètres spécifiés.

```csharp
public IImage GetImage(ITiffOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | ITiffOptions | Options Tiff. |

### Valeur de retour

Objet Image.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Lancée lorsque options.SlideLayoutOption est NotesCommentsLayoutingOptions et sa propriété NotesPosition prend la valeur NotesPositions.BottomFull. |

### Voir Aussi

* interface [IImage](../../iimage)
* interface [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

Renvoie un objet Image Thumbnail.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | IRenderingOptions | Options de rendu. |

### Valeur de retour

Objet Image.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Lancée lorsque notesCommentsLayouting.NotesPosition prend la valeur NotesPositions.BottomFull |

### Voir Aussi

* interface [IImage](../../iimage)
* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

Renvoie un objet Image Thumbnail avec un scaling personnalisé.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | IRenderingOptions | Options de rendu. |
| scaleX | Single | La valeur par laquelle scalier ce Thumbnail dans la direction de l'axe x. |
| scaleY | Single | La valeur par laquelle scalier ce Thumbnail dans la direction de l'axe y. |

### Valeur de retour

Objets Bitmap.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Lancée lorsque notesCommentsLayouting.NotesPosition prend la valeur NotesPositions.BottomFull |

### Exemples

L'exemple suivant montre comment convertir des diapositives avec des notes et des commentaires en Images en utilisant C#.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // Créer les options de rendu
    IRenderingOptions options = new RenderingOptions();
    // Créer des options de mise en page pour les notes et les commentaires
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // Définit la position des notes sur la page
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // Définit la position des commentaires sur la page
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // Définit la largeur de la zone de sortie des commentaires
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // Définit la couleur de la zone des commentaires
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // Définir les options de mise en page pour le rendu
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // Convertit la première diapositive de la présentation en un objet IImage
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // Enregistre l'image au format GIF
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### Voir Aussi

* interface [IImage](../../iimage)
* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

Renvoie un objet Image Thumbnail avec une taille spécifiée.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | IRenderingOptions | Options de rendu. |
| imageSize | Size | Taille de l'image à créer. |

### Valeur de retour

Objet Image.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Lancée lorsque options.SlideLayoutOption est NotesCommentsLayoutingOptions et sa propriété NotesPosition prend la valeur NotesPositions.BottomFull. |

### Voir Aussi

* interface [IImage](../../iimage)
* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->