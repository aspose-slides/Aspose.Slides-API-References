---
title: AddChartPlaceholder
second_title: Aspose.Slides pour .NET Référence API
description: Ajoute une nouvelle forme de contenu à la diapositive de mise en page pour contenir un graphique.
type: docs
weight: 10
url: /fr/aspose.slides/layoutplaceholdermanager/addchartplaceholder/
---

## LayoutPlaceholderManager.AddChartPlaceholder méthode

Ajoute une nouvelle forme de contenu à la diapositive de mise en page pour contenir un graphique.

```csharp
public IAutoShape AddChartPlaceholder(float x, float y, float width, float height)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| x | Single | La coordonnée X de la nouvelle forme de contenu. |
| y | Single | La coordonnée Y de la nouvelle forme de contenu. |
| width | Single | La largeur de la nouvelle forme de contenu. |
| height | Single | La hauteur de la nouvelle forme de contenu. |

### Valeur de retour

Créé [`IAutoShape`](../../iautoshape) avec un espace réservé pour un graphique.

### Exemples

L'exemple suivant montre comment ajouter la forme d'espace réservé pour le graphique à la diapositive de mise en page.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
	ILayoutSlide layout = pres.LayoutSlides.GetByType(SlideLayoutType.Blank);
	IAutoShape placeholder = layout.PlaceholderManager.AddChartPlaceholder(20, 20, 200, 200);
}
```

### Voir aussi

* interface [IAutoShape](../../iautoshape)
* classe [LayoutPlaceholderManager](../../layoutplaceholdermanager)
* namespace [Aspose.Slides](../../layoutplaceholdermanager)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->