---
title: AddPictureFrame()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un nouveau cadre d'image contenant l'image spécifiée et l'ajoute à la fin de la collection de formes.
type: docs
weight: 404
url: /fr/aspose.slides/ishapecollection/addpictureframe/
---
## IShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) méthode

Crée un nouveau cadre d'image contenant l'image spécifiée et l'ajoute à la fin de la collection de formes.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Spécifie le type de forme contenu dans [ShapeType](../../shapetype/), à l'exception de toutes les sortes de lignes :

[ShapeType::Line](../../shapetype/),

[ShapeType::StraightConnector1](../../shapetype/),

[ShapeType::BentConnector2](../../shapetype/),

[ShapeType::BentConnector3](../../shapetype/),

[ShapeType::BentConnector4](../../shapetype/),

[ShapeType::BentConnector5](../../shapetype/),

[ShapeType::CurvedConnector2](../../shapetype/),

[ShapeType::CurvedConnector3](../../shapetype/),

[ShapeType::CurvedConnector4](../../shapetype/),

[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | La coordonnée x du cadre d'image, en points. |
| y | **float** | La coordonnée y du cadre d'image, en points. |
| width | **float** | La largeur du cadre d'image, en points. |
| height | **float** | La hauteur du cadre d'image, en points. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Le [IPPImage](../../ippimage/) à afficher dans le cadre d'image. |

### Valeur de retour

Le [IPictureFrame](../../ipictureframe/) nouvellement créé.

## Voir aussi

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPictureFrame](../../ipictureframe/)
* Classe [IPPImage](../../ippimage/)
* Classe [IShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)