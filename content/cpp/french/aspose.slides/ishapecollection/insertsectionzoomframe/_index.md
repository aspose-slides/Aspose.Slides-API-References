---
title: InsertSectionZoomFrame()
second_title: Référence API Aspose.Slides pour C++
description: Crée un nouveau cadre Section Zoom et l'insère dans la collection de formes à l'index spécifié.
type: docs
weight: 131
url: /fr/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) method


Crée un nouveau [Section](../../section/) cadre Zoom et l'insère dans la collection de formes à l'index spécifié.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index basé sur zéro où insérer le cadre Zoom [Section](../../section/). |
| x | **float** | La coordonnée x du nouveau cadre Zoom [Section](../../section/), en points. |
| y | **float** | La coordonnée y du nouveau cadre Zoom [Section](../../section/), en points. |
| width | **float** | La largeur du nouveau cadre Zoom [Section](../../section/), en points. |
| height | **float** | La hauteur du nouveau cadre Zoom [Section](../../section/), en points. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) référencé par le cadre Zoom [Section](../../section/) ; doit appartenir à cette présentation et contenir au moins une diapositive. |

### Valeur de retour

Le [ISectionZoomFrame](../../isectionzoomframe/) nouvellement créé.

## Remarques


Cet exemple montre la création et l'insertion d'un objet Zoom [Section](../../section/) à l'index spécifié d'une collection (supposez qu'il y a au moins deux sections dans la présentation "Presentation.pptx") : 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) method


Crée un nouveau [Section](../../section/) cadre Zoom avec une image prédéfinie et l'insère dans la collection de formes à l'index spécifié.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index basé sur zéro où insérer le cadre Zoom [Section](../../section/). |
| x | **float** | La coordonnée x du nouveau cadre Zoom [Section](../../section/), en points. |
| y | **float** | La coordonnée y du nouveau cadre Zoom [Section](../../section/), en points. |
| width | **float** | La largeur du nouveau cadre Zoom [Section](../../section/), en points. |
| height | **float** | La hauteur du nouveau cadre Zoom [Section](../../section/), en points. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [ISection](../../isection/) référencé par le cadre Zoom [Section](../../section/) ; doit appartenir à cette présentation et contenir au moins une diapositive. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | L'image à afficher dans le cadre Zoom [Section](../../section/). |

### Valeur de retour

Le [ISectionZoomFrame](../../isectionzoomframe/) nouvellement créé.

## Remarques


Cet exemple montre la création et l'insertion d'un objet Zoom [Section](../../section/) à l'index spécifié d'une collection (supposez qu'il y a au moins deux sections dans la présentation "Presentation.pptx") : 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISectionZoomFrame](../../isectionzoomframe/)
* Class [ISection](../../isection/)
* Class [IShapeCollection](../)
* Class [IPPImage](../../ippimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)