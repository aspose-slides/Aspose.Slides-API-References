---
title: AddContentPlaceholder()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute une nouvelle forme d'espace réservé à la diapositive de mise en page pour contenir du contenu, tel qu'une image, un tableau, des médias ou du texte.
type: docs
weight: 1
url: /fr/aspose.slides/layoutplaceholdermanager/addcontentplaceholder/
---
## LayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) méthode


Ajoute une nouvelle forme de zone réservée à la diapositive de mise en page pour contenir du contenu, tel qu'une image, un tableau, des médias ou du texte.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée X de la nouvelle forme de zone réservée. |
| y | **float** | La coordonnée Y de la nouvelle forme de zone réservée. |
| width | **float** | La largeur de la nouvelle forme de zone réservée. |
| height | **float** | La hauteur de la nouvelle forme de zone réservée. |

### Valeur de retour

Créé [IAutoShape](../../iautoshape/) avec une zone réservée de type Content.
## Remarques



L'exemple suivant montre comment ajouter la forme de zone réservée Content à la diapositive de mise en page. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [LayoutPlaceholderManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)