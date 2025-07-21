---
title: AddGroupShape()
second_title: Aspose.Slides for C++ API Reference
description: Creates a new empty group shape and adds it to the end of the shape collection. The group\\u2019s frame will automatically adjust to fit any shapes added to it.
type: docs
weight: 391
url: /aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() method


Creates a new empty group shape and adds it to the end of the shape collection. The group\\u2019s frame will automatically adjust to fit any shapes added to it.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```


### Return Value

The newly created [IGroupShape](../../igroupshape/).
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

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) method


Creates a new group shape, converts the specified SVG image into individual shapes, and adds the resulting group to the end of the shape collection.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | The [ISvgImage](../../isvgimage/) containing vector content to convert into shapes. |
| x | **float** | The x-coordinate of the group\\u2019s frame, in points. |
| y | **float** | The y-coordinate of the group\\u2019s frame, in points. |
| width | **float** | The width of the group\\u2019s frame, in points. |
| height | **float** | The height of the group\\u2019s frame, in points. |

### Return Value

The newly created [IGroupShape](../../igroupshape/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGroupShape](../../igroupshape/)
* Class [ShapeCollection](../)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)