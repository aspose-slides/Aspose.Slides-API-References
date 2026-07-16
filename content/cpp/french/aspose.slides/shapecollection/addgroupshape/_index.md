---
title: AddGroupShape()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une nouvelle forme de groupe vide et l’ajoute à la fin de la collection de formes. Le cadre du groupe s’ajustera automatiquement pour contenir toutes les formes qui y sont ajoutées.
type: docs
weight: 391
url: /fr/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() méthode


Crée une nouvelle forme de groupe vide et l’ajoute à la fin de la collection de formes. Le cadre du groupe s’ajustera automatiquement pour contenir toutes les formes qui y sont ajoutées.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```


### Valeur de retour

Le [IGroupShape](../../igroupshape/) nouvellement créé.
## Remarques



L’exemple suivant montre comment ajouter une forme de groupe à une diapositive PowerPoint [Presentation](../../presentation/). 
```cpp
// Instancier la classe Presentation
auto pres = System::MakeObject<Presentation>();

// Obtenir la première diapositive
auto slide = pres->get_Slides()->idx_get(0);
// Accéder à la collection de formes des diapositives
auto slideShapes = slide->get_Shapes();
// Ajouter une forme de groupe à la diapositive
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// Ajouter des formes dans la forme de groupe ajoutée
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// Ajouter le cadre de la forme de groupe
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// Écrire le fichier PPTX sur le disque
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) méthode


Crée une nouvelle forme de groupe, convertit l’image SVG spécifiée en formes individuelles, et ajoute le groupe résultant à la fin de la collection de formes.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Le [ISvgImage](../../isvgimage/) contenant le contenu vectoriel à convertir en formes. |
| x | **float** | La coordonnée x du cadre du groupe, en points. |
| y | **float** | La coordonnée y du cadre du groupe, en points. |
| width | **float** | La largeur du cadre du groupe, en points. |
| height | **float** | La hauteur du cadre du groupe, en points. |

### Valeur de retour

Le [IGroupShape](../../igroupshape/) nouvellement créé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IGroupShape](../../igroupshape/)
* Classe [ShapeCollection](../)
* Classe [ISvgImage](../../isvgimage/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)