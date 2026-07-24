---
title: AddGroupShape()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt ein neues leeres Gruppen-Shape und fügt es am Ende der Shape-Collection hinzu. Der Rahmen der Gruppe wird automatisch angepasst, um alle hinzugefügten Shapes aufzunehmen.
type: docs
weight: 391
url: /de/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() Methode

Erstellt ein neues leeres Gruppen-Shape und fügt es am Ende der shape collection hinzu. Der group\\u2019s frame wird automatisch angepasst, um alle hinzugefügten Shapes aufzunehmen.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```

### Rückgabewert

Das neu erstellte [IGroupShape](../../igroupshape/).

## Hinweise



Das folgende Beispiel zeigt, wie man ein Gruppen-Shape zu einer Folie von PowerPoint [Presentation](../../presentation/) hinzufügt. 
```cpp
// Instanziiere die Presentation-Klasse
auto pres = System::MakeObject<Presentation>();

// Hole die erste Folie
auto slide = pres->get_Slides()->idx_get(0);
// Zugriff auf die Shape-Collection der Folien
auto slideShapes = slide->get_Shapes();
// Hinzufügen eines Gruppen-Shape zur Folie
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// Hinzufügen von Shapes innerhalb des hinzugefügten Gruppen-Shape
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// Hinzufügen des Gruppen-Shape-Frames
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// Schreibe die PPTX-Datei auf die Festplatte
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) Methode


Erstellt ein neues Gruppen-Shape, konvertiert das angegebene SVG-Bild in einzelne Shapes und fügt die resultierende Gruppe am Ende der shape collection hinzu.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Das [ISvgImage](../../isvgimage/) enthält Vektorinhalt, der in Shapes konvertiert werden soll. |
| x | **float** | Die x-Koordinate des group\\u2019s frames, in Punkten. |
| y | **float** | Die y-Koordinate des group\\u2019s frames, in Punkten. |
| width | **float** | Die Breite des group\\u2019s frames, in Punkten. |
| height | **float** | Die Höhe des group\\u2019s frames, in Punkten. |

### Rückgabewert

Das neu erstellte [IGroupShape](../../igroupshape/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IGroupShape](../../igroupshape/)
* Klasse [ShapeCollection](../)
* Klasse [ISvgImage](../../isvgimage/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)