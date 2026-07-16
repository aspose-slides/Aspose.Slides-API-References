---
title: AddChartPlaceholder()
second_title: Référence API Aspose.Slides pour C++
description: Ajoute une nouvelle forme d'espace réservé à la diapositive de mise en page pour contenir un graphique.
type: docs
weight: 66
url: /fr/aspose.slides/layoutplaceholdermanager/addchartplaceholder/
---
## LayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) méthode


Ajoute une nouvelle forme d'espace réservé à la diapositive de mise en page pour contenir un graphique.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée X de la nouvelle forme d'espace réservé. |
| y | **float** | La coordonnée Y de la nouvelle forme d'espace réservé. |
| width | **float** | La largeur de la nouvelle forme d'espace réservé. |
| height | **float** | La hauteur de la nouvelle forme d'espace réservé. |

### Valeur de retour

Créé [IAutoShape](../../iautoshape/) avec un espace réservé Chart.
## Remarques



L'exemple suivant montre comment ajouter la forme d'espace réservé Chart à la diapositive de mise en page. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [LayoutPlaceholderManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)