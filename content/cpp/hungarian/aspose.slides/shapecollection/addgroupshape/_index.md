---
title: AddGroupShape()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy új üres csoport alakzatot, és a shape collection végéhez adja hozzá. A csoport kerete automatikusan igazodik, hogy minden hozzáadott alakzatra illeszkedjen.
type: docs
weight: 391
url: /hu/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() metódus


Létrehoz egy új üres csoport alakzatot, és a shape collection végéhez adja hozzá. A csoport kerete automatikusan igazodik, hogy minden hozzáadott alakzatra illeszkedjen.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```


### Visszatérési érték

Az újonnan létrehozott [IGroupShape](../../igroupshape/).
## Megjegyzések



A következő példa bemutatja, hogyan lehet csoport alakzatot hozzáadni egy PowerPoint [Presentation](../../presentation/) diára. 
```cpp
// A Presentation osztály példányosítása
auto pres = System::MakeObject<Presentation>();

// Az első dia lekérése
auto slide = pres->get_Slides()->idx_get(0);
// A diák alakzatgyűjteményének elérése
auto slideShapes = slide->get_Shapes();
// Csoport alakzat hozzáadása a diához
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// Alakzatok hozzáadása a hozzáadott csoport alakzathoz
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// Csoport alakzat keretének hozzáadása
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// A PPTX fájl írása a lemezre
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) metódus


Létrehoz egy új csoport alakzatot, átalakítja a megadott SVG képet egyedi alakzatokká, és az így kapott csoportot a shape collection végéhez adja hozzá.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | A [ISvgImage](../../isvgimage/) amely vektortartalmat tartalmaz, alakzatokká konvertálható. |
| x | **float** | A csoport keretének x-koordinátája pontban. |
| y | **float** | A csoport keretének y-koordinátája pontban. |
| width | **float** | A csoport keretének szélessége pontban. |
| height | **float** | A csoport keretének magassága pontban. |

### Visszatérési érték

Az újonnan létrehozott [IGroupShape](../../igroupshape/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IGroupShape](../../igroupshape/)
* Osztály [ShapeCollection](../)
* Osztály [ISvgImage](../../isvgimage/)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)