---
title: AddZoomFrame()
second_title: Référence API Aspose.Slides pour C++
description: Crée un nouveau cadre Zoom et l'ajoute à la fin de la collection de formes.
type: docs
weight: 105
url: /fr/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) method

Crée un nouveau cadre Zoom et l’ajoute à la fin de la collection de formes.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x du nouveau cadre Zoom, en points. |
| y | **float** | La coordonnée y du nouveau cadre Zoom, en points. |
| width | **float** | La largeur du nouveau cadre Zoom, en points. |
| height | **float** | La hauteur du nouveau cadre Zoom, en points. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Le [ISlide](../../islide/) référencé par le cadre Zoom ; il doit appartenir à cette présentation. |

### Valeur de retour

Le [IZoomFrame](../../izoomframe/) nouvellement créé.

## Remarques

Cet exemple montre comment ajouter un objet Zoom à la fin d’une collection (supposons qu’il y ait au moins deux diapositives dans la présentation « Presentation.pptx ») : 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) method

Crée un nouveau cadre Zoom et l’ajoute à la fin de la collection de formes.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x du nouveau cadre Zoom, en points. |
| y | **float** | La coordonnée y du nouveau cadre Zoom, en points. |
| width | **float** | La largeur du nouveau cadre Zoom, en points. |
| height | **float** | La hauteur du nouveau cadre Zoom, en points. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Le [ISlide](../../islide/) référencé par le cadre Zoom ; il doit appartenir à cette présentation. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | L’image de la diapositive référencée [IPPImage](../../ippimage/). |

### Valeur de retour

Le [IZoomFrame](../../izoomframe/) nouvellement créé.

## Remarques

Cet exemple montre comment ajouter un objet Zoom à la fin d’une collection (supposons qu’il y ait au moins deux diapositives dans la présentation « Presentation.pptx ») : 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IZoomFrame](../../izoomframe/)
* Classe [ISlide](../../islide/)
* Classe [ShapeCollection](../)
* Classe [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)