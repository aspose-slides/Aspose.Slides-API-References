---
title: AddContentPlaceholder()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une nouvelle forme d'espace réservé à la diapositive de mise en page pour contenir du contenu, tel qu'une image, un tableau, un média ou du texte.
type: docs
weight: 1
url: /fr/aspose.slides/ilayoutplaceholdermanager/addcontentplaceholder/
---
## ILayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) méthode

Ajoute une nouvelle forme d’espace réservé à la diapositive de disposition pour contenir du contenu, tel qu’une image, un tableau, un média ou du texte.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée X de la nouvelle forme d’espace réservé. |
| y | **float** | La coordonnée Y de la nouvelle forme d’espace réservé. |
| width | **float** | La largeur de la nouvelle forme d’espace réservé. |
| height | **float** | La hauteur de la nouvelle forme d’espace réservé. |

### Valeur de retour

Créé [IAutoShape](../../iautoshape/) avec un espace réservé de contenu.

## Remarques

L’exemple suivant montre comment ajouter la forme d’espace réservé de contenu à la diapositive de disposition. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [ILayoutPlaceholderManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)