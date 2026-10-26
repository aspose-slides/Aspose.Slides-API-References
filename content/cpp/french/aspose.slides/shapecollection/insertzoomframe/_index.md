---
title: InsertZoomFrame()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un nouveau cadre Zoom et l'insère dans la collection de formes à l'index spécifié.
type: docs
weight: 118
url: /fr/aspose.slides/shapecollection/insertzoomframe/
---
## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) méthode


Crée un nouveau cadre Zoom et l'insère dans la collection de formes à l'index spécifié.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index de base zéro à lequel insérer le cadre Zoom. |
| x | **float** | La coordonnée x du nouveau cadre Zoom, en points. |
| y | **float** | La coordonnée y du nouveau cadre Zoom, en points. |
| width | **float** | La largeur du nouveau cadre Zoom, en points. |
| height | **float** | La hauteur du nouveau cadre Zoom, en points. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Le [ISlide](../../islide/) référencé par le cadre Zoom. |

### Valeur de retour

Le [IZoomFrame](../../izoomframe/) nouvellement créé.

## Remarques


Cet exemple montre la création et l'insertion d'un objet Zoom à l'index spécifié d'une collection (supposez qu'il y a au moins deux diapositives dans la présentation "Presentation.pptx") : 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) méthode


Crée un nouveau cadre Zoom avec une image prédéfinie et l'insère dans la collection de formes à l'index spécifié.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index de base zéro à lequel insérer le cadre Zoom. |
| x | **float** | La coordonnée x du nouveau cadre Zoom, en points. |
| y | **float** | La coordonnée y du nouveau cadre Zoom, en points. |
| width | **float** | La largeur du nouveau cadre Zoom, en points. |
| height | **float** | La hauteur du nouveau cadre Zoom, en points. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Le [ISlide](../../islide/) référencé par le cadre Zoom. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | L'image pour la diapositive référencée [IPPImage](../../ippimage/). |

### Valeur de retour

Le [IZoomFrame](../../izoomframe/) nouvellement créé.

## Remarques


Cet exemple montre la création et l'insertion d'un objet Zoom à l'index spécifié d'une collection (supposez qu'il y a au moins deux diapositives dans la présentation "Presentation.pptx") : 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```


## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IZoomFrame](../../izoomframe/)
* Classe [ISlide](../../islide/)
* Classe [ShapeCollection](../)
* Classe [IPPImage](../../ippimage/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)