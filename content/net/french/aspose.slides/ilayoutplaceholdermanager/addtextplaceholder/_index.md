---
title: AddTextPlaceholder
second_title: Référence de l'API Aspose.Slides pour .NET
description: Ajoute une nouvelle forme de remplissage au diapositive de mise en page pour contenir du texte.
type: docs
weight: 80
url: /fr/aspose.slides/ilayoutplaceholdermanager/addtextplaceholder/
---

## ILayoutPlaceholderManager.AddTextPlaceholder méthode

Ajoute une nouvelle forme de remplissage au diapositive de mise en page pour contenir du texte.

```csharp
public IAutoShape AddTextPlaceholder(float x, float y, float width, float height)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| x | Single | La coordonnée X de la nouvelle forme de remplissage. |
| y | Single | La coordonnée Y de la nouvelle forme de remplissage. |
| width | Single | La largeur de la nouvelle forme de remplissage. |
| height | Single | La hauteur de la nouvelle forme de remplissage. |

### Valeur de Retour

Créé [`IAutoShape`](../../iautoshape) avec un remplissage de texte.

### Exemples

L'exemple suivant montre comment ajouter la forme de remplissage de texte à la diapositive de mise en page.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
	ILayoutSlide layout = pres.LayoutSlides.GetByType(SlideLayoutType.Blank);
	IAutoShape placeholder = layout.PlaceholderManager.AddTextPlaceholder(20, 20, 500, 300);
}
```

### Voir Aussi

* interface [IAutoShape](../../iautoshape)
* interface [ILayoutPlaceholderManager](../../ilayoutplaceholdermanager)
* namespace [Aspose.Slides](../../ilayoutplaceholdermanager)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->