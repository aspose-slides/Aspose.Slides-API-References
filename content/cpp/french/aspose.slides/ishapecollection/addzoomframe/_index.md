---
title: AddZoomFrame()
second_title: Aspose.Slides pour C++ Référence API
description: Crée un nouveau cadre Zoom et l'ajoute à la fin de la collection de formes.
type: docs
weight: 92
url: /fr/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) method

Crée un nouveau cadre Zoom et l'ajoute à la fin de la collection de formes.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x du nouveau cadre Zoom, en points. |
| y | **float** | La coordonnée y du nouveau cadre Zoom, en points. |
| width | **float** | La largeur du nouveau cadre Zoom, en points. |
| height | **float** | La hauteur du nouveau cadre Zoom, en points. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Le [ISlide](../../islide/) référencé par le cadre Zoom ; il doit appartenir à cette présentation. |

### Return Value

Le [IZoomFrame](../../izoomframe/) nouvellement créé.

## Remarks

Cet exemple montre comment ajouter un objet Zoom à la fin d’une collection (supposons qu’il y a au moins deux diapositives dans la présentation "Presentation.pptx") : 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) method

Crée un nouveau cadre Zoom et l'ajoute à la fin de la collection de formes.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x du nouveau cadre Zoom, en points. |
| y | **float** | La coordonnée y du nouveau cadre Zoom, en points. |
| width | **float** | La largeur du nouveau cadre Zoom, en points. |
| height | **float** | La hauteur du nouveau cadre Zoom, en points. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Le [ISlide](../../islide/) référencé par le cadre Zoom ; il doit appartenir à cette présentation. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | L’image pour la diapositive référencée [IPPImage](../../ippimage/). |

### Return Value

Le [IZoomFrame](../../izoomframe/) nouvellement créé.

## Remarks

Cet exemple montre comment ajouter un objet Zoom à la fin d’une collection (supposons qu’il y a au moins deux diapositives dans la présentation "Presentation.pptx") : 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IZoomFrame](../../izoomframe/)
* Class [ISlide](../../islide/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)