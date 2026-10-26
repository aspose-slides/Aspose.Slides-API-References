---
title: AddConnector()
second_title: Aspose.Slides C++ API hivatkozás
description: Létrehoz egy új csatlakozó alakzatot az alapértelmezett sablon stílussal, és a alakzatgyűjtemény végéhez adja.
type: docs
weight: 417
url: /hu/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) metódus

Létrehoz egy új csatlakozó alakzatot az alapértelmezett sablon stílussal, és a alakzatgyűjtemény végéhez adja.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | A [ShapeType](../../shapetype/) a hozzáadandó csatlakozó alakzat. |
| x | **float** | A connector\u2019s keret x-koordinátája pontban. |
| y | **float** | A connector\u2019s keret y-koordinátája pontban. |
| width | **float** | A connector\u2019s keret szélessége pontban. |
| height | **float** | A connector\u2019s keret magassága pontban. |

### Visszatérési érték

Az újonnan létrehozott [IConnector](../../iconnector/).

## Megjegyzések

A következő példa bemutatja, hogyan kell egy csatlakozót (egy hajlított csatlakozót) két alakzat (egy ellipszis és egy téglalap) között hozzáadni a PowerPoint [Presentation](../../presentation/)-ban.

```cpp
// Létrehoz egy prezentáció osztályt, amely egy PPTX fájlt képvisel
auto input = System::MakeObject<Presentation>();

// Eléri a formák gyűjteményét egy adott dián
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// Hozzáad egy Ellipse autoshape-et
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// Hozzáad egy Rectangle autoshape-et
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// Hozzáad egy csatlakozó alakzatot a dia formagyűjteményéhez
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// Összekapcsolja a formákat a csatlakozóval
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// Meghívja a reroute-ot, amely beállítja a formák közötti automatikus legrövidebb útvonalat
connector->Reroute();

// Elmenti a prezentációt
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) metódus

Létrehoz egy új csatlakozó alakzatot, és a alakzatgyűjtemény végéhez adja, opcionálisan az alapértelmezett sablon stílus alkalmazásával.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | A [ShapeType](../../shapetype/) a létrehozandó csatlakozó alakzat. |
| x | **float** | A connector\u2019s keret x-koordinátája pontban. |
| y | **float** | A connector\u2019s keret y-koordinátája pontban. |
| width | **float** | A connector\u2019s keret szélessége pontban. |
| height | **float** | A connector\u2019s keret magassága pontban. |
| createFromTemplate | **bool** | Igaz az alapértelmezett sablon stílus alkalmazásához (nem üres név, egyszerű stílus); hamis a csatlakozó alapértelmezett tulajdonságértékekkel való létrehozásához. |

### Visszatérési érték

Az újonnan létrehozott [IConnector](../../iconnector/).

## Lásd még

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)