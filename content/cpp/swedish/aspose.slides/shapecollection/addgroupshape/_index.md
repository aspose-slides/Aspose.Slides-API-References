---
title: AddGroupShape()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny tom gruppform och lägger till den i slutet av formsamlingen. Gruppens ram justeras automatiskt för att passa alla former som läggs till i den.
type: docs
weight: 391
url: /sv/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() metod

Skapar en ny tom gruppform och lägger till den i slutet av formsamlingen. Gruppens ram justeras automatiskt för att passa alla former som läggs till i den.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```

### Returvärde

Den nyss skapade [IGroupShape](../../igroupshape/).
## Anmärkningar

Följande exempel visar hur man lägger till en gruppform i en PowerPoint-bild [Presentation](../../presentation/).
```cpp
// Instansiera Presentation-klass
auto pres = System::MakeObject<Presentation>();

// Hämta den första bilden
auto slide = pres->get_Slides()->idx_get(0);
// Åtkomst till bildens formsamling
auto slideShapes = slide->get_Shapes();
// Lägger till en gruppform på bilden
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// Lägger till former i den tillagda gruppformen
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// Lägger till gruppformens ram
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// Skriver PPTX-filen till disk
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) metod

Skapar en ny gruppform, konverterar den angivna SVG-bilden till individuella former och lägger till den resulterande gruppen i slutet av formsamlingen.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/) som innehåller vektor innehåll att konvertera till former. |
| x | **float** | X-koordinaten för gruppens ram, i punkter. |
| y | **float** | Y-koordinaten för gruppens ram, i punkter. |
| width | **float** | Bredden på gruppens ram, i punkter. |
| height | **float** | Höjden på gruppens ram, i punkter. |

### Returvärde

Den nyss skapade [IGroupShape](../../igroupshape/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGroupShape](../../igroupshape/)
* Class [ShapeCollection](../)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)