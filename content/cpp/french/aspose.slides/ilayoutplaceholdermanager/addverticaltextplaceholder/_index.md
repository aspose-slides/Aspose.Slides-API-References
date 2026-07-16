---
title: AddVerticalTextPlaceholder()
second_title: Référence API Aspose.Slides pour C++
description: Ajoute une nouvelle forme d'espace réservé à la diapositive de mise en page pour contenir du texte en direction verticale.
type: docs
weight: 40
url: /fr/aspose.slides/ilayoutplaceholdermanager/addverticaltextplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) method


Ajoute une nouvelle forme d'espace réservé à la diapositive de mise en page pour contenir du texte en direction verticale.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée X de la nouvelle forme d'espace réservé. |
| y | **float** | La coordonnée Y de la nouvelle forme d'espace réservé. |
| width | **float** | La largeur de la nouvelle forme d'espace réservé. |
| height | **float** | La hauteur de la nouvelle forme d'espace réservé. |

### Valeur de retour

Créé [IAutoShape](../../iautoshape/) avec un espace réservé de texte (Vertical).

## Remarques



L'exemple suivant montre comment ajouter la forme d'espace réservé de texte (Vertical) à la diapositive de mise en page. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [ILayoutPlaceholderManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)