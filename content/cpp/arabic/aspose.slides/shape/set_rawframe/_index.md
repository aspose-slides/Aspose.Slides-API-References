---
title: set_RawFrame()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضبط خصائص إطار الشكل الخام. اكتب IShapeFrame.
type: docs
weight: 53
url: /ar/aspose.slides/shape/set_rawframe/
---
## Shape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) طريقة

يضبط خصائص إطار الشكل الخام. اكتب [IShapeFrame](../../ishapeframe/).

```cpp
void Aspose::Slides::Shape::set_RawFrame(System::SharedPtr<IShapeFrame> value) override
```

## ملاحظات

الكود الذي يحاول تعيين إطار غير معرف إلى [IShape::set_Frame](../../ishape/set_frame/) لا معنى له في الحالة العامة (وخاصةً في الحالة التي يكون فيها الوالد [GroupShape](../../groupshape/) متداخلًا عدة مرات في GroupShape أخرى). على سبيل المثال:
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
هذا الكود قد يؤدي إلى حالات غير واضحة. لذلك تمت إضافة قيود لاستخدام قيم غير معرفة لـ [IShape::set_Frame](../../ishape/set_frame/). يجب تعريف قيم x, y, width, height, flipH, flipV و rotationAngle (ليس std::numeric_limits<float>::quiet_NaN() أو [NullableBool::NotDefined](../../nullablebool/)). الكود المثال أعلاه الآن يطلق استثناء ArgumentException. ينطبق هذا على حالات الاستخدام التالية:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // لا يمكن أن يكون غير معرف

SharedPtr<IShapeCollection> shapes = ...;
// معاملات x, y, العرض, الارتفاع لا يمكن أن تكون std::numeric_limits<float>::quiet_NaN():
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

لكن يمكن أن يكون الإطار لطريقة [IShape::set_RawFrame](../../ishape/set_rawframe/) غير معرف. هذا منطقي عندما يكون الشكل مرتبطًا بمكان حامل. ثم يتم تجاوز قيم إطار الشكل غير المعرف من قبل شكل المكان الحامل الأب. إذا لم يكن هناك شكل مكان حامل أب لهذا الشكل فإن ذلك الشكل يستخدم القيم الافتراضية عند تقييم الإطار الفعال بناءً على [IShape::get_RawFrame](../../ishape/get_rawframe/). القيم الافتراضية هي 0 و [NullableBool::False](../../nullablebool/) لـ x, y, width, height, flipH, flipV و rotationAngle. على سبيل المثال:
```cpp
SharedPtr<IShape> shape = ...; // الشكل مرتبط بمكان حامل
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // الآن يرث الشكل قيم x, y, الارتفاع, flipH, flipV من المكان الحامل ويتجاوز قيمة العرض = 100 وزاوية الدوران = 0.
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* صف [IShapeFrame](../../ishapeframe/)
* صف [Shape](../)
* مساحة الاسم [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)