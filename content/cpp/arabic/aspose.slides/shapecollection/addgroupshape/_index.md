---
title: AddGroupShape()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ شكل مجموعة فارغ جديد ويضيفه إلى نهاية مجموعة الأشكال. سيقوم إطار المجموعة تلقائيًا بضبط نفسه ليتناسب مع أي أشكال تُضاف إليه.
type: docs
weight: 391
url: /ar/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() طريقة

Creates a new empty group shape and adds it to the end of the shape collection. The group\u2019s frame will automatically adjust to fit any shapes added to it.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```

### قيمة الإرجاع

The newly created [IGroupShape](../../igroupshape/).
## ملاحظات

The following example shows how to add a group shape to a slide of PowerPoint [Presentation](../../presentation/). 
```cpp
// إنشاء كائن فئة Presentation
auto pres = System::MakeObject<Presentation>();

// الحصول على الشريحة الأولى
auto slide = pres->get_Slides()->idx_get(0);
// الوصول إلى مجموعة الأشكال للشرائح
auto slideShapes = slide->get_Shapes();
// إضافة شكل مجموعة إلى الشريحة
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// إضافة أشكال داخل مجموعة الأشكال المضافة
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// إضافة إطار مجموعة الأشكال
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// حفظ ملف PPTX على القرص
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) طريقة

Creates a new group shape, converts the specified SVG image into individual shapes, and adds the resulting group to the end of the shape collection.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```

### المعلمات

| معلمة | نوع | وصف |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | The [ISvgImage](../../isvgimage/) containing vector content to convert into shapes. |
| x | **float** | The x-coordinate of the group\u2019s frame, in points. |
| y | **float** | The y-coordinate of the group\u2019s frame, in points. |
| width | **float** | The width of the group\u2019s frame, in points. |
| height | **float** | The height of the group\u2019s frame, in points. |

### قيمة الإرجاع

The newly created [IGroupShape](../../igroupshape/).

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [IGroupShape](../../igroupshape/)
* فئة [ShapeCollection](../)
* فئة [ISvgImage](../../isvgimage/)
* مساحة الأسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)