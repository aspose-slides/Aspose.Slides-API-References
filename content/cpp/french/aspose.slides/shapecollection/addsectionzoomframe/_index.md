---
title: AddSectionZoomFrame()
second_title: Référence API Aspose.Slides pour C++
description: Crée un nouveau cadre Section Zoom et l'ajoute à la fin de la collection de formes.
type: docs
weight: 131
url: /fr/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) méthode

Crée un nouveau cadre Zoom [Section](../../section/) et l’ajoute à la fin de la collection de formes.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x du nouveau cadre Zoom [Section](../../section/), en points. |
| y | **float** | La coordonnée y du nouveau cadre Zoom [Section](../../section/), en points. |
| width | **float** | La largeur du nouveau cadre Zoom [Section](../../section/), en points. |
| height | **float** | La hauteur du nouveau cadre Zoom [Section](../../section/), en points. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Le [ISection](../../isection/) référencé par le cadre Zoom [Section](../../section/) ; il doit appartenir à cette présentation et contenir au moins une diapositive. |

### Valeur de retour

Le [ISectionZoomFrame](../../isectionzoomframe/) nouvellement créé.

## Remarques

Cet exemple montre comment ajouter un objet Zoom [Section](../../section/) à la fin d’une collection (supposez qu’il y a au moins deux sections dans la présentation « Presentation.pptx ») :
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) méthode

Crée un nouveau cadre Zoom [Section](../../section/) avec une image prédéfinie et l’ajoute à la fin de la collection de formes.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x du nouveau cadre Zoom [Section](../../section/), en points. |
| y | **float** | La coordonnée y du nouveau cadre Zoom [Section](../../section/), en points. |
| width | **float** | La largeur du nouveau cadre Zoom [Section](../../section/), en points. |
| height | **float** | La hauteur du nouveau cadre Zoom [Section](../../section/), en points. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Le [ISection](../../isection/) référencé par le cadre Zoom [Section](../../section/) ; il doit appartenir à cette présentation et contenir au moins une diapositive. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Le [IPPImage](../../ippimage/) à afficher dans le cadre Zoom [Section](../../section/). |

### Valeur de retour

Le [ISectionZoomFrame](../../isectionzoomframe/) nouvellement créé.

## Remarques

Cet exemple montre comment ajouter un objet Zoom [Section](../../section/) à la fin d’une collection (supposez qu’il y a au moins deux sections dans la présentation « Presentation.pptx ») :
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISectionZoomFrame](../../isectionzoomframe/)
* Classe [ISection](../../isection/)
* Classe [ShapeCollection](../)
* Classe [IPPImage](../../ippimage/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)