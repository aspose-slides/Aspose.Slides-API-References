---
title: set_RawFrame()
second_title: مرجع Aspose.Slides API للغة C++
description: يعين خصائص إطار الشكل الخام. اكتب IShapeFrame.
type: docs
weight: 53
url: /ar/aspose.slides/ishape/set_rawframe/
---
## IShape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) طريقة


يضبط خصائص إطار الشكل الخام. اكتب [IShapeFrame](../../ishapeframe/).

```cpp
virtual void Aspose::Slides::IShape::set_RawFrame(System::SharedPtr<IShapeFrame> value)=0
```

## ملاحظات


الشفرة التي تحاول تعيين إطار غير معرف إلى [IShape::set_Frame](../set_frame/) لا معنى لها في الحالة العامة (وخاصةً في الحالة التي يكون فيها الأصل [GroupShape](../../groupshape/) متداخلًا متعددةً في أشكال مجموعة أخرى). على سبيل المثال:
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
مثل هذا الكود يمكن أن يؤدي إلى مواقف غير واضحة. لذلك تمت إضافة قيود لاستخدام القيم غير المعرفة لـ [IShape::set_Frame](../set_frame/). يجب تعريف قيم x, y, width, height, flipH, flipV و rotationAngle (ليس std::numeric_limits<float>::quiet_NaN() أو [NullableBool::NotDefined](../../nullablebool/)). الآن الكود المذكور أعلاه يطرح استثناء ArgumentException. هذا ينطبق على حالات الاستخدام التالية:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // لا يمكن أن تكون غير معرفة

SharedPtr<IShapeCollection> shapes = ...;
// معلمات x, y, width, height لا يمكن أن تكون std::numeric_limits<float>::quiet_NaN():
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


لكن الإطار لطريقة [IShape::set_RawFrame](./) يمكن أن يكون غير معرف. هذا منطقي عندما يكون الشكل مرتبطًا بعنصر نائب. ثم تُستبدل قيم إطار الشكل غير المعرفة من شكل العنصر النائب الأصل. إذا لم يكن هناك عنصر نائب أصلي لذلك الشكل، فإن الشكل يستخدم القيم الافتراضية عند تقييم الإطار الفعّال بناءً على [IShape::get_RawFrame](../get_rawframe/). القيم الافتراضية هي 0 و [NullableBool::False](../../nullablebool/) لـ x, y, width, height, flipH, flipV و rotationAngle. على سبيل المثال:
```cpp
SharedPtr<IShape> shape = ...; // الشكل مرتبط بالعنصر النائب
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // الآن يرث الشكل قيم x, y, height, flipH, flipV من العنصر النائب ويتجاوز width=100 و rotationAngle=0.
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IShapeFrame](../../ishapeframe/)
* فئة [IShape](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)