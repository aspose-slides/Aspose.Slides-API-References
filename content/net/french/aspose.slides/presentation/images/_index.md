---
title: Images
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Renvoie la collection de toutes les images de la présentation. Lecture seule IImageCollectionaspose.slides/iimagecollection.
type: docs
weight: 140
url: /fr/aspose.slides/presentation/images/
---

## Propriété Presentation.Images

Renvoie la collection de toutes les images dans la présentation. Lecture seule [`IImageCollection`](../../iimagecollection).

```csharp
public IImageCollection Images { get; }
```

### Exemples

Les exemples suivants montrent comment ajouter une image sous forme de BLOB dans une présentation PowerPoint.

```csharp
[C#]
string pathToLargeImage = "large_image.jpg";
// crée une nouvelle présentation à laquelle l'image sera ajoutée.
using (Presentation pres = new Presentation())
{
	using (FileStream fileStream = new FileStream(pathToLargeImage, FileMode.Open))
	{
		// Ajoutons l'image à la présentation - nous choisissons le comportement KeepLocked car nous n'avons
		// PAS l'intention d'accéder au fichier "largeImage.png".
		IPPImage img = pres.Images.AddImage(fileStream, LoadingStreamBehavior.KeepLocked);
		pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
		// Enregistre la présentation. Bien qu'une grande présentation soit produite, la consommation de mémoire
		// reste faible tout au long du cycle de vie de l'objet pres
		pres.Save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
	}
}
```

Les exemples suivants ajoutent un hyperlien à une image dans une présentation PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    // Ajoute l'image à la présentation
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.png"));
    // Crée un cadre d'image sur la diapositive 1 basé sur l'image précédemment ajoutée
    IPictureFrame pictureFrame = pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    pictureFrame.HyperlinkClick = new Hyperlink("https://www.aspose.com/");
    pictureFrame.HyperlinkClick.Tooltip = "Plus de 70 % des entreprises du Fortune 100 font confiance aux API Aspose";
    pres.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

### Voir aussi

* interface [IImageCollection](../../iimagecollection)
* classe [Presentation](../../presentation)
* espace de noms [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->