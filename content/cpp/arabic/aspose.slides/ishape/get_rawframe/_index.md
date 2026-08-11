---
title: get_RawFrame()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرجع خصائص إطار الشكل الخام. اقرأ IShapeFrame.
type: docs
weight: 40
url: /ar/aspose.slides/ishape/get_rawframe/
---
## IShape::get_RawFrame() طريقة

يُعيد خصائص إطار الشكل الخام. اقرأ [IShapeFrame](../../ishapeframe/).

```cpp
virtual System::SharedPtr<IShapeFrame> Aspose::Slides::IShape::get_RawFrame()=0
```

## ملاحظات

الشفرة التي تحاول إسناد إطار غير معرف إلى [IShape::set_Frame](../set_frame/) لا معنى لها في الحالة العامة (وخاصةً في حالة عندما يكون الوالد [GroupShape](../../groupshape/) متداخلاً عدة مرات داخل GroupShape-s أخرى). على سبيل المثال:
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
 قد يتسبب مثل هذا الشيفرة في مواقف غير واضحة. لذا تمت إضافة قيود لاستخدام القيم غير المعرفة لـ [IShape::set_Frame](../set_frame/). يجب تعريف قيم x و y والعرض والارتفاع و flipH و flipV و rotationAngle (ليس std::numeric_limits<float>::quiet_NaN() أو [NullableBool::NotDefined](../../nullablebool/)). الآن يتسبب الشيفرة المثال أعلاه في رفع استثناء ArgumentException. ينطبق هذا على حالات الاستخدام التالية:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // لا يمكن أن تكون غير معرفة

SharedPtr<IShapeCollection> shapes = ...;
// معلمات x, y, العرض, الارتفاع لا يمكن أن تكون std::numeric_limits<float>::quiet_NaN():
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

لكن الإطار الخاص بطريقة [IShape::set_RawFrame](../set_rawframe/) يمكن أن يكون غير معرف. هذا منطقي عندما يكون الشكل مرتبطًا بـ placeholder. ثم تُستبدل قيم إطار الشكل غير المعرفة من قبل شكل placeholder الأب. إذا لم يكن هناك شكل placeholder أب لهذا الشكل فإن ذلك الشكل يستخدم القيم الافتراضية عند تقييم الإطار الفعلي بناءً على [IShape::get_RawFrame](./). القيم الافتراضية هي 0 و [NullableBool::False](../../nullablebool/) لـ x و y والعرض والارتفاع و flipH و flipV و rotationAngle. على سبيل المثال:
```cpp
SharedPtr<IShape> shape = ...; // الشكل مرتبط بـ placeholder
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // الآن الشكل يرث قيم x, y, height, flipH, flipV من placeholder ويتجاوز width=100 و rotationAngle=0.
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IShapeFrame](../../ishapeframe/)
* فئة [IShape](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)