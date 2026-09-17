---
title: insert_picture_frame method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ishapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
Crée un nouveau cadre d'image contenant l'image spécifiée et l'insère dans la collection de formes à l'index indiqué.

### Retour

Le nouvellement créé [`IPictureFrame`](/slides/python-net/fr/aspose.slides/ipictureframe).



```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L'index basé à zéro à lequel insérer le cadre d'image. |
| shape_type | [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) | Spécifie le type de forme contenu dans [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype),<br/><br/>            sauf pour tous les types de lignes:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | La coordonnée x du cadre d'image, en points. |
| y | **float** | La coordonnée y du cadre d'image, en points. |
| width | **float** | La largeur du cadre d'image, en points. |
| height | **float** | La hauteur du cadre d'image, en points. |
| image | [`IPPImage`](/slides/python-net/fr/aspose.slides/ippimage) | Le [`IPPImage`](/slides/python-net/fr/aspose.slides/ippimage) à afficher dans le cadre d'image. |



### Voir aussi
* classe [`IPictureFrame`](/slides/python-net/fr/aspose.slides/ipictureframe)
* classe [`IPPImage`](/slides/python-net/fr/aspose.slides/ippimage)
* classe [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection)
* énumération [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)