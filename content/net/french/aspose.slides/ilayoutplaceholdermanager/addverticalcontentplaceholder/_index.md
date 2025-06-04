---
title: AddVerticalContentPlaceholder
second_title: Référence de l'API Aspose.Slides pour .NET
description: Ajoute une nouvelle forme de zone réservée à la diapositive de mise en page pour contenir du contenu tel qu'une image, un tableau, un média ou du texte dans une direction verticale.
type: docs
weight: 90
url: /fr/aspose.slides/ilayoutplaceholdermanager/addverticalcontentplaceholder/
---

## ILayoutPlaceholderManager.AddVerticalContentPlaceholder méthode

Ajoute une nouvelle forme de zone réservée à la diapositive de mise en page pour contenir du contenu, tel qu'une image, un tableau, un média ou du texte dans une direction verticale.

```csharp
public IAutoShape AddVerticalContentPlaceholder(float x, float y, float width, float height)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| x | Single | La coordonnée X de la nouvelle forme de zone réservée. |
| y | Single | La coordonnée Y de la nouvelle forme de zone réservée. |
| width | Single | La largeur de la nouvelle forme de zone réservée. |
| height | Single | La hauteur de la nouvelle forme de zone réservée. |

### Valeur de retour

Créé [`IAutoShape`](../../iautoshape) avec une zone réservée (Verticale) de Contenu.

### Exemples

L'exemple suivant montre comment ajouter la forme de zone réservée de Contenu (Vertical) à la diapositive de mise en page.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
	ILayoutSlide layout = pres.LayoutSlides.GetByType(SlideLayoutType.Blank);
	IAutoShape placeholder = layout.PlaceholderManager.AddVerticalContentPlaceholder(20, 20, 300, 500);
}
```

### Voir aussi

* interface [IAutoShape](../../iautoshape)
* interface [ILayoutPlaceholderManager](../../ilayoutplaceholdermanager)
* namespace [Aspose.Slides](../../ilayoutplaceholdermanager)
* assembly [Aspose.Slides](../../../)