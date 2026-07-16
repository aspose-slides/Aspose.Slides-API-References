---
title: get_HeaderFooterManager()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie le gestionnaire HeaderFooter actuel. Lecture seule IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /fr/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() méthode


Renvoie le gestionnaire HeaderFooter actuel. Lecture seule [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## Remarques


L'exemple suivant montre comment définir la visibilité du pied de page à l'intérieur de [Slide](../../slide/) de PowerPoint [Presentation](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// La propriété IsFooterVisible est utilisée pour indiquer qu'un espace réservé de pied de page de diapositive n'est pas présent.
if (!headerFooterManager->get_IsFooterVisible())
{
    // La méthode SetFooterVisibility est utilisée pour rendre visible un espace réservé de pied de page de diapositive.
    headerFooterManager->SetFooterVisibility(true);
}

// La propriété IsSlideNumberVisible est utilisée pour indiquer qu'un espace réservé du numéro de page de diapositive n'est pas présent.
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // La méthode SetSlideNumberVisibility est utilisée pour rendre visible un espace réservé du numéro de page de diapositive.
    headerFooterManager->SetSlideNumberVisibility(true);
}

// La propriété IsDateTimeVisible est utilisée pour indiquer qu'un espace réservé de date-heure de diapositive n'est pas présent.
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // La méthode SetFooterVisibility est utilisée pour rendre visible un espace réservé de date-heure de diapositive.
    headerFooterManager->SetDateTimeVisibility(true);
}

// La méthode SetFooterText est utilisée pour définir le texte du pied de page de la diapositive.
headerFooterManager->SetFooterText(u"Footer text");
// La méthode SetDateTimeText est utilisée pour définir le texte de l'espace réservé de date-heure de la diapositive.
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
 L'exemple suivant montre comment définir la visibilité du pied de page enfant à l'intérieur de [Slide](../../slide/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// La méthode SetFooterAndChildFootersVisibility est utilisée pour rendre visible le master slide et tous les espaces réservés de pied de page enfants.
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// La méthode SetSlideNumberAndChildSlideNumbersVisibility est utilisée pour rendre visible le master slide et tous les espaces réservés de numéro de page enfants.
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// La méthode SetDateTimeAndChildDateTimesVisibility est utilisée pour rendre visible le master slide et tous les espaces réservés de date-heure enfants.
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// La méthode SetFooterAndChildFootersText est utilisée pour définir le texte du master slide et de tous les espaces réservés de pied de page enfants.
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// La méthode SetDateTimeAndChildDateTimesText est utilisée pour définir le texte du master slide et de tous les espaces réservés de date-heure enfants.
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* Classe [Presentation](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)