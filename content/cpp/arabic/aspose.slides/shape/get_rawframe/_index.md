---
title: get_RawFrame()
second_title: Aspose.Slides لـ C++ مرجع API
description: يعيد خصائص إطار الشكل الخام. اقرأ IShapeFrame.
type: docs
weight: 40
url: /ar/aspose.slides/shape/get_rawframe/
---
## Shape::get_RawFrame() طريقة

يعيد خصائص إطار الشكل الخام. اقرأ [IShapeFrame](../../ishapeframe/).

```cpp
System::SharedPtr<IShapeFrame> Aspose::Slides::Shape::get_RawFrame() override
```

## ملاحظات

الكود الذي يحاول تعيين إطار غير معرف إلى [IShape::set_Frame](../../ishape/set_frame/) لا معنى له في الحالة العامة (وخاصةً عندما يكون العنصر الأب [GroupShape](../../groupshape/) متداخلًا عدة مرات داخل GroupShape-s). على سبيل المثال:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
أو
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
مثل هذا الكود قد يؤدي إلى أوضاع غير واضحة. لذلك تمت إضافة قيود لاستخدام القيم غير المعرفة لـ [IShape::set_Frame](../../ishape/set_frame/). يجب تعريف قيم x و y و width و height و flipH و flipV و rotationAngle (ليس std::numeric_limits<float>::quiet_NaN() أو [NullableBool::NotDefined](../../nullablebool/)). الكود المثال أعلاه الآن يرمى استثناء ArgumentException. هذا ينطبق على حالات الاستخدام التالية:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // لا يمكن أن تكون غير معرفة

SharedPtr<IShapeCollection> shapes = ...;
// معلمات x و y و width و height لا يمكن أن تكون std::numeric_limits<float>::quiet_NaN():
{
    shapes->AddAudioFrameCD(...);
    shapes->AddAudioFrameEmbedded(...);
    shapes->AddAudioFrameLinked(...);
    shapes->AddAutoShape(...);
    shapes->AddChart(...);
    shapes->AddConnector(...);
    shapes->AddOleObjectFrame(...);
    shapes->AddPictureFrame(...);
    shapes->AddSmartArt(...);
    shapes->AddTable(...);
    shapes->AddVideoFrame(...);
    shapes->InsertAudioFrameEmbedded(...);
    shapes->InsertAudioFrameLinked(...);
    shapes->InsertAutoShape(...);
    shapes->InsertChart(...);
    shapes->InsertConnector(...);
    shapes->InsertOleObjectFrame(...);
    shapes->InsertPictureFrame(...);
    shapes->InsertTable(...);
    shapes->InsertVideoFrame(...);
}
```

لكن الإطار لطريقة [IShape::set_RawFrame](../../ishape/set_rawframe/) يمكن أن يكون غير معرف. هذا منطقي عندما يكون الشكل مرتبطًا بالعنصر النائب. ثم يتم استبدال قيم إطار الشكل غير المعرفة من الشكل النائب الأب. إذا لم يكن هناك شكل نائب أب لهذا الشكل، فإن هذا الشكل يستخدم القيم الافتراضية عند تقييم الإطار الفعلي بناءً على [IShape::get_RawFrame](../../ishape/get_rawframe/). القيم الافتراضية هي 0 و [NullableBool::False](../../nullablebool/) لـ x و y و width و height و flipH و flipV و rotationAngle. على سبيل المثال:
```cpp
SharedPtr<IShape> shape = ...; // الشكل مرتبط بالعنصر النائب
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // الآن الشكل يرث قيم x و y و height و flipH و flipV من العنصر النائب ويستبدل width=100 و rotationAngle=0.
```

## راجع أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [IShapeFrame](../../ishapeframe/)
* الفئة [Shape](../)
* النطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)