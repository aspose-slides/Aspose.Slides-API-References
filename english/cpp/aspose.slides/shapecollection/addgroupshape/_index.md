---
title: AddGroupShape()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new GroupShape and adds it to the end of the collection. GroupShape frame size and position will be fitted to content when new shape will be added into the GroupShape.
type: docs
weight: 391
url: /cpp/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() method


Creates a new [GroupShape](../../groupshape/) and adds it to the end of the collection. [GroupShape](../../groupshape/) frame size and position will be fitted to content when new shape will be added into the [GroupShape](../../groupshape/).

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```


### Return Value

Created [GroupShape](../../groupshape/) object.
## Remarks



The following example shows how to add a group shape to a slide of PowerPoint [Presentation](../../presentation/). 
```cpp
// Instantiate Presentation class
auto pres = System::MakeObject<Presentation>();

// Get the first slide
auto slide = pres->get_Slides()->idx_get(0);
// Accessing the shape collection of slides
auto slideShapes = slide->get_Shapes();
// Adding a group shape to the slide
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// Adding shapes inside added group shape
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// Adding group shape frame
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// Write the PPTX file to disk
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGroupShape](../../igroupshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
## ShapeCollection::AddGroupShape([System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\>, **float**, **float**, **float**, **float**) method


Creates a new [GroupShape](../../groupshape/), fills it with converted shapes from SVG and adds it to the end of the collection.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Svg image object [ISvgImage](../../isvgimage/) |
| x | **float** | The X coordinate for the left side of the shape group frame. |
| y | **float** | The Y coordinate for the top side of the shape group frame. |
| width | **float** | The width of the group of the shape group frame. |
| height | **float** | The height of a group of the shape group frame. |

### Return Value

Created [GroupShape](../../groupshape/) object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGroupShape](../../igroupshape/)
* Class [ISvgImage](../../isvgimage/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
