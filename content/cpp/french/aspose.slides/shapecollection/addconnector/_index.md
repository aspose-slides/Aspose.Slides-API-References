---
title: AddConnector()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une nouvelle forme de connecteur avec le style de modèle par défaut et l'ajoute à la fin de la collection de formes.
type: docs
weight: 417
url: /fr/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) méthode

Crée une nouvelle forme de connecteur avec le style de modèle par défaut et l'ajoute à la fin de la collection de formes.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Le [ShapeType](../../shapetype/) de la forme de connecteur à ajouter. |
| x | **float** | La coordonnée x du cadre du connecteur, en points. |
| y | **float** | La coordonnée y du cadre du connecteur, en points. |
| width | **float** | La largeur du cadre du connecteur, en points. |
| height | **float** | La hauteur du cadre du connecteur, en points. |

### Valeur de retour

Le [IConnector](../../iconnector/) nouvellement créé.

## Remarques

L'exemple suivant montre comment ajouter un connecteur (un connecteur coudé) entre deux formes (une ellipse et un rectangle) dans PowerPoint [Presentation](../../presentation/). 
```cpp
// Instancie une classe de présentation qui représente un fichier PPTX
auto input = System::MakeObject<Presentation>();

// Accède à la collection de formes d'une diapositive spécifique
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// Ajoute une forme automatique Ellipse
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// Ajoute une forme automatique Rectangle
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// Ajoute une forme de connecteur à la collection de formes de la diapositive
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// Connecte les formes à l'aide du connecteur
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// Appelle reroute qui définit le chemin le plus court automatique entre les formes
connector->Reroute();

// Enregistre la présentation
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) méthode

Crée une nouvelle forme de connecteur et l'ajoute à la fin de la collection de formes, en appliquant éventuellement le style de modèle par défaut.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Le [ShapeType](../../shapetype/) de la forme de connecteur à créer. |
| x | **float** | La coordonnée x du cadre du connecteur, en points. |
| y | **float** | La coordonnée y du cadre du connecteur, en points. |
| width | **float** | La largeur du cadre du connecteur, en points. |
| height | **float** | La hauteur du cadre du connecteur, en points. |
| createFromTemplate | **bool** | Vrai pour appliquer le style de modèle par défaut (nom non vide, style simple) ; false pour créer le connecteur avec les valeurs de propriété par défaut. |

### Valeur de retour

Le [IConnector](../../iconnector/) nouvellement créé.

## Voir aussi

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IConnector](../../iconnector/)
* Classe [ShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)