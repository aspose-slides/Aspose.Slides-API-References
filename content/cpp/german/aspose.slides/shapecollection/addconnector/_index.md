---
title: AddConnector()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Connector-Shape mit Standardvorlagenstil und fügt sie am Ende der ShapeCollection hinzu.
type: docs
weight: 417
url: /de/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) method


Erstellt eine neue Connectorform mit dem Standardvorlagenstil und fügt sie am Ende der ShapeCollection hinzu.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Der [ShapeType](../../shapetype/) des zu hinzufügenden Connector-Shapes. |
| x | **float** | Die x-Koordinate des Rahmens des Connectors, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens des Connectors, in Punkten. |
| width | **float** | Die Breite des Rahmens des Connectors, in Punkten. |
| height | **float** | Die Höhe des Rahmens des Connectors, in Punkten. |

### Rückgabewert

Das neu erstellte [IConnector](../../iconnector/).

## Hinweise



Das folgende Beispiel zeigt, wie man einen Connector (einen gekrümmten Connector) zwischen zwei Formen (einer Ellipse und einem Rechteck) in PowerPoint [Presentation](../../presentation/) hinzufügt. 
```cpp
// Instanziiert eine Präsentationsklasse, die eine PPTX-Datei darstellt
auto input = System::MakeObject<Presentation>();

// Greift auf die Shape-Sammlung einer bestimmten Folie zu
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// Fügt eine Ellipse-Autoform hinzu
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// Fügt eine Rechteck-Autoform hinzu
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// Fügt der Shape-Sammlung der Folie eine Connector-Form hinzu
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// Verbindet die Formen mithilfe des Connectors
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// Ruft Reroute auf, das den automatischen kürzesten Pfad zwischen den Formen festlegt
connector->Reroute();

// Speichert die Präsentation
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) method


Erstellt eine neue Connectorform und fügt sie am Ende der ShapeCollection hinzu, wobei optional der Standardvorlagenstil angewendet wird.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Der [ShapeType](../../shapetype/) des zu erstellenden Connector-Shapes. |
| x | **float** | Die x-Koordinate des Rahmens des Connectors, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens des Connectors, in Punkten. |
| width | **float** | Die Breite des Rahmens des Connectors, in Punkten. |
| height | **float** | Die Höhe des Rahmens des Connectors, in Punkten. |
| createFromTemplate | **bool** | True, um den Standardvorlagenstil anzuwenden (nicht leerer Name, einfacher Stil); false, um den Connector mit den Standardwerteigenschaften zu erstellen. |

### Rückgabewert

Das neu erstellte [IConnector](../../iconnector/).

## Siehe auch

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)