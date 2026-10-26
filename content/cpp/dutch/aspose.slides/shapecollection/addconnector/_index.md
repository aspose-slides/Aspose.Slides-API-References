---
title: AddConnector()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuwe connectorvorm met standaard-template-styling en voegt deze toe aan het einde van de shape-collectie.
type: docs
weight: 417
url: /nl/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) methode

Maakt een nieuwe connectorvorm met standaard-templates styling en voegt deze toe aan het einde van de shape-collectie.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | De [ShapeType](../../shapetype/) van de toe te voegen connectorvorm. |
| x | **float** | De x-coördinaat van het frame van de connector, in punten. |
| y | **float** | De y-coördinaat van het frame van de connector, in punten. |
| width | **float** | De breedte van het frame van de connector, in punten. |
| height | **float** | De hoogte van het frame van de connector, in punten. |

### Retourwaarde

De nieuw gemaakte [IConnector](../../iconnector/).

## Opmerkingen

Het volgende voorbeeld toont hoe je een connector (een gebogen connector) tussen twee vormen (een ellips en een rechthoek) toevoegt in PowerPoint [Presentation](../../presentation/). 
```cpp
// Instantieert een presentatieklasse die een PPTX-bestand voorstelt
auto input = System::MakeObject<Presentation>();

// Toegang tot de shape-collectie voor een specifieke dia
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// Voegt een Ellipse-autoshape toe
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// Voegt een Rectangle-autoshape toe
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// Voegt een connector-shape toe aan de shape-collectie van de dia
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// Verbindt de shapes met de connector
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// Roept reroute aan die het automatische kortste pad tussen shapes instelt
connector->Reroute();

// Slaat de presentatie op
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) methode

Maakt een nieuwe connectorvorm en voegt deze toe aan het einde van de shape-collectie, met de optie om standaard-templates styling toe te passen.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | De [ShapeType](../../shapetype/) van de te creëren connectorvorm. |
| x | **float** | De x-coördinaat van het frame van de connector, in punten. |
| y | **float** | De y-coördinaat van het frame van de connector, in punten. |
| width | **float** | De breedte van het frame van de connector, in punten. |
| height | **float** | De hoogte van het frame van de connector, in punten. |
| createFromTemplate | **bool** | True om standaard-templates styling toe te passen (niet-lege naam, eenvoudige stijl); false om de connector te maken met standaard waarde-eigenschappen. |

### Retourwaarde

De nieuw gemaakte [IConnector](../../iconnector/).

## Zie ook

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)