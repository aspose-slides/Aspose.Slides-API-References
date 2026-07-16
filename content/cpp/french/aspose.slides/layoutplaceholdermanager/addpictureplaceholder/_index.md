---
title: AddPicturePlaceholder()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une nouvelle forme d'espace réservé à la diapositive de mise en page pour contenir une image.
type: docs
weight: 53
url: /fr/aspose.slides/layoutplaceholdermanager/addpictureplaceholder/
---
## LayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) méthode

Ajoute une nouvelle forme d’espace réservé à la diapositive de mise en page pour contenir une image.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée X de la nouvelle forme d’espace réservé. |
| y | **float** | La coordonnée Y de la nouvelle forme d’espace réservé. |
| width | **float** | La largeur de la nouvelle forme d’espace réservé. |
| height | **float** | La hauteur de la nouvelle forme d’espace réservé. |

### Valeur de retour

Créé [IAutoShape](../../iautoshape/) avec un espace réservé [Picture](../../picture/).

## Remarques

L’exemple suivant montre comment ajouter la forme d’espace réservé [Picture](../../picture/) à la diapositive de mise en page. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [LayoutPlaceholderManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)