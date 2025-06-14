---
title: HeaderFooterManager
second_title: Aspose.Slides pour la référence API .NET
description: Retourne le gestionnaire HeaderFooter actuel. Lecture seule IPresentationHeaderFooterManageraspose.slides/ipresentationheaderfootermanager.
type: docs
weight: 120
url: /fr/aspose.slides/presentation/headerfootermanager/
---

## Propriété Presentation.HeaderFooterManager

Retourne le gestionnaire HeaderFooter actuel. Lecture seule [`IPresentationHeaderFooterManager`](../../ipresentationheaderfootermanager).

```csharp
public IPresentationHeaderFooterManager HeaderFooterManager { get; }
```

### Exemples

L'exemple suivant montre comment définir la visibilité du pied de page à l'intérieur d'une diapositive d'une présentation PowerPoint.

```csharp
[C#]
using (Presentation presentation = new Presentation("presentation.ppt"))
{
    IBaseSlideHeaderFooterManager headerFooterManager = presentation.Slides[0].HeaderFooterManager;
	// La propriété IsFooterVisible est utilisée pour indiquer qu'un espace réservé de pied de page pour une diapositive n'est pas présent.
    if (!headerFooterManager.IsFooterVisible)
    {
		// La méthode SetFooterVisibility est utilisée pour rendre un espace réservé de pied de page pour une diapositive visible.
        headerFooterManager.SetFooterVisibility(true);
    }
	// La propriété IsSlideNumberVisible est utilisée pour indiquer qu'un espace réservé de numéro de page pour une diapositive n'est pas présent.
    if (!headerFooterManager.IsSlideNumberVisible)
    {
		// La méthode SetSlideNumberVisibility est utilisée pour rendre un espace réservé de numéro de page pour une diapositive visible.
        headerFooterManager.SetSlideNumberVisibility(true);
    }
	// La propriété IsDateTimeVisible est utilisée pour indiquer qu'un espace réservé de date-heure pour une diapositive n'est pas présent.
    if (!headerFooterManager.IsDateTimeVisible)
    {
		// La méthode SetFooterVisibility est utilisée pour rendre un espace réservé de date-heure pour une diapositive visible.
        headerFooterManager.SetDateTimeVisibility(true);
    }
	// La méthode SetFooterText est utilisée pour définir le texte dans l'espace réservé de pied de page pour une diapositive.
    headerFooterManager.SetFooterText("Texte du pied de page");
	// La méthode SetDateTimeText est utilisée pour définir le texte dans l'espace réservé de date-heure pour une diapositive.
    headerFooterManager.SetDateTimeText("Texte de la date et de l'heure");
	presentation.Save("Presentation.ppt",SaveFormat.ppt);
}
```

L'exemple suivant montre comment définir la visibilité du pied de page enfant à l'intérieur d'une diapositive.

```csharp
[C#]
using (Presentation presentation = new Presentation("presentation.ppt"))
{
    IMasterSlideHeaderFooterManager headerFooterManager = presentation.Masters[0].HeaderFooterManager;
	// La méthode SetFooterAndChildFootersVisibility est utilisée pour rendre une diapositive maître et tous les espaces réservés de pied de page enfant visibles.
    headerFooterManager.SetFooterAndChildFootersVisibility(true);
	// La méthode SetSlideNumberAndChildSlideNumbersVisibility est utilisée pour rendre une diapositive maître et tous les espaces réservés de numéro de page enfant visibles.
    headerFooterManager.SetSlideNumberAndChildSlideNumbersVisibility(true);
	// La méthode SetDateTimeAndChildDateTimesVisibility est utilisée pour rendre une diapositive maître et tous les espaces réservés de date-heure enfant visibles.
    headerFooterManager.SetDateTimeAndChildDateTimesVisibility(true);
	// La méthode SetFooterAndChildFootersText est utilisée pour définir le texte dans la diapositive maître et tous les espaces réservés de pied de page enfant.
    headerFooterManager.SetFooterAndChildFootersText("Texte du pied de page");
	// La méthode SetDateTimeAndChildDateTimesText est utilisée pour définir le texte dans la diapositive maître et tous les espaces réservés de date-heure enfant.
    headerFooterManager.SetDateTimeAndChildDateTimesText("Texte de la date et de l'heure");
}
```

### Voir aussi

* interface [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->