---
title: InsertPictureFrame()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un nouveau cadre d'image contenant l'image spécifiée et l'insère dans la collection de formes à l'index spécifié.
type: docs
weight: 456
url: /fr/aspose.slides/shapecollection/insertpictureframe/
---
## ShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) méthode

Crée un nouveau cadre d'image contenant l'image spécifiée et l'insère dans la collection de formes à l'index spécifié.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index basé sur zéro à lequel insérer le cadre d'image. |
| shapeType | [ShapeType](../../shapetype/) | Spécifie le type de forme contenu dans [ShapeType](../../shapetype/), sauf pour tous les types de lignes :

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

* Énum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPictureFrame](../../ipictureframe/)
* Classe [IPPImage](../../ippimage/)
* Classe [ShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)