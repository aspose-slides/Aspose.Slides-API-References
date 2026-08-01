---
title: AddGroupShape()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw lege groepvorm en voegt deze toe aan het einde van de shape-collectie. Het frame van de groep wordt automatisch aangepast om alle toegevoegde vormen te bevatten.
type: docs
weight: 391
url: /nl/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() method


Maakt een nieuw lege groepvorm en voegt deze toe aan het einde van de shape-collectie. Het frame van de groep wordt automatisch aangepast om alle toegevoegde vormen te bevatten.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```


### Retourwaarde

De nieuw aangemaakte [IGroupShape](../../igroupshape/).
## Opmerkingen



Het volgende voorbeeld toont hoe u een groepvorm toevoegt aan een dia van PowerPoint [Presentation](../../presentation/). 
```cpp
// Instantieer de Presentation-klasse
auto pres = System::MakeObject<Presentation>();

// Haal de eerste dia op
auto slide = pres->get_Slides()->idx_get(0);
// Toegang tot de vormverzameling van dia's
auto slideShapes = slide->get_Shapes();
// Voeg een groepvorm toe aan de dia
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// Voeg vormen toe binnen de toegevoegde groepvorm
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// Voeg groepvormframe toe
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// Schrijf het PPTX-bestand naar schijf
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) method


Maakt een nieuw groepvorm, converteert de opgegeven SVG-afbeelding naar afzonderlijke vormen, en voegt de resulterende groep toe aan het einde van de shape-collectie.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | De [ISvgImage](../../isvgimage/) met vectorinhoud die moet worden omgezet in vormen. |
| x | **float** | De x-coördinaat van het frame van de groep, in punten. |
| y | **float** | De y-coördinaat van het frame van de groep, in punten. |
| width | **float** | De breedte van het frame van de groep, in punten. |
| height | **float** | De hoogte van het frame van de groep, in punten. |

### Retourwaarde

De nieuw aangemaakte [IGroupShape](../../igroupshape/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGroupShape](../../igroupshape/)
* Class [ShapeCollection](../)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)