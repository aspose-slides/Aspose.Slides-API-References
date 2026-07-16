---
title: InsertSectionZoomFrame()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un nouveau cadre de zoom de section et l'insère dans la collection de formes à l'index spécifié.
type: docs
weight: 144
url: /fr/aspose.slides/shapecollection/insertsectionzoomframe/
---
## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) method


Crée un nouveau [Section](../../section/) Zoom frame et l’insère dans la collection de formes à l’index spécifié.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L’indice de base zéro à laquelle insérer le [Section](../../section/) Zoom frame. |
| x | **float** | La coordonnée x du nouveau [Section](../../section/) Zoom frame, en points. |
| y | **float** | La coordonnée y du nouveau [Section](../../section/) Zoom frame, en points. |
| width | **float** | La largeur du nouveau [Section](../../section/) Zoom frame, en points. |
| height | **float** | La hauteur du nouveau [Section](../../section/) Zoom frame, en points. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Le [ISection](../../isection/) référencé par le [Section](../../section/) Zoom frame ; il doit appartenir à cette présentation et contenir au moins une diapositive. |

### Valeur de retour

Le [ISectionZoomFrame](../../isectionzoomframe/) nouvellement créé.

## Remarques


Cet exemple montre la création et l’insertion d’un [Section](../../section/) Zoom object à l’index spécifié d’une collection (supposez qu’il y a au moins deux sections dans la présentation "Presentation.pptx") : 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) method


Crée un nouveau [Section](../../section/) Zoom frame avec une image prédéfinie et l’insère dans la collection de formes à l’index spécifié.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L’indice de base zéro à laquelle insérer le [Section](../../section/) Zoom frame. |
| x | **float** | La coordonnée x du nouveau [Section](../../section/) Zoom frame, en points. |
| y | **float** | La coordonnée y du nouveau [Section](../../section/) Zoom frame, en points. |
| width | **float** | La largeur du nouveau [Section](../../section/) Zoom frame, en points. |
| height | **float** | La hauteur du nouveau [Section](../../section/) Zoom frame, en points. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Le [ISection](../../isection/) référencé par le [Section](../../section/) Zoom frame ; il doit appartenir à cette présentation et contenir au moins une diapositive. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | L’image à afficher dans le [Section](../../section/) Zoom frame. |

### Valeur de retour

Le [ISectionZoomFrame](../../isectionzoomframe/) nouvellement créé.

## Remarques


Cet exemple montre la création et l’insertion d’un [Section](../../section/) Zoom object à l’index spécifié d’une collection (supposez qu’il y a au moins deux sections dans la présentation "Presentation.pptx") : 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISectionZoomFrame](../../isectionzoomframe/)
* Classe [ISection](../../isection/)
* Classe [ShapeCollection](../)
* Classe [IPPImage](../../ippimage/)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)