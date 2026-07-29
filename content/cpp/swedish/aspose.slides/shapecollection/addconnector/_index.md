---
title: AddConnector()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny connector-form med standardmallstil och lägger till den i slutet av formsamlingen.
type: docs
weight: 417
url: /sv/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) metod

Skapar en ny kopplingsform med standardmallstil och lägger till den i slutet av formsamlingen.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Den [ShapeType](../../shapetype/) för den connector\\u2019s form som ska läggas till. |
| x | **float** | x-koordinaten för connector\\u2019s ram, i punkter. |
| y | **float** | y-koordinaten för connector\\u2019s ram, i punkter. |
| width | **float** | bredden på connector\\u2019s ram, i punkter. |
| height | **float** | höjden på connector\\u2019s ram, i punkter. |

### Return Value

Den nyss skapade [IConnector](../../iconnector/).

## Anmärkningar

Följande exempel visar hur man lägger till en connector (en böjd connector) mellan två former (en ellips och en rektangel) i PowerPoint [Presentation](../../presentation/). 
```cpp
// Instansierar en presentationsklass som representerar en PPTX-fil
auto input = System::MakeObject<Presentation>();

// Åtkommer formsamlingen för en specifik bild
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// Lägger till en Ellipse-autoshape
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// Lägger till en Rectangle-autoshape
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// Lägger till en connector-form i bildens formsamling
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// Kopplar samman formerna med connectorn
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// Anropar Reroute som ställer in den automatiska kortaste vägen mellan formerna
connector->Reroute();

// Sparar presentationen
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) metod

Skapar en ny connector-form och lägger till den i slutet av formsamlingen, med möjlighet att tillämpa standardmallstil.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Den [ShapeType](../../shapetype/) för den connector\\u2019s form som ska skapas. |
| x | **float** | x-koordinaten för connector\\u2019s ram, i punkter. |
| y | **float** | y-koordinaten för connector\\u2019s ram, i punkter. |
| width | **float** | bredden på connector\\u2019s ram, i punkter. |
| height | **float** | höjden på connector\\u2019s ram, i punkter. |
| createFromTemplate | **bool** | True för att tillämpa standardmallstil (icke-tomt namn, enkel stil); false för att skapa connector-formen med standardegenskapsvärden. |

### Return Value

Den nyss skapade [IConnector](../../iconnector/).

## Se Also

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)