---
title: get_RawFrame()
second_title: Aspose.Slides برای مرجع API C++
description: ویژگی‌های چارچوب خام شکل را برمی‌گرداند. بخوانید IShapeFrame.
type: docs
weight: 40
url: /fa/aspose.slides/shape/get_rawframe/
---
## Shape::get_RawFrame() متد

ویژگی‌های چارچوب خام شکل را برمی‌گرداند. بخوانید [IShapeFrame](../../ishapeframe/).

```cpp
System::SharedPtr<IShapeFrame> Aspose::Slides::Shape::get_RawFrame() override
```

## توضیحات

کدی که سعی می‌کند چارچوب تعریف‌نشده را به [IShape::set_Frame](../../ishape/set_frame/) اختصاص دهد، در حالت کلی معنا ندارد (به‌ویژه در موردی که والد [GroupShape](../../groupshape/) به‌صورت چندگانه در سایر GroupShape-ها تو در تو باشد). برای مثال:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
 یا 
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
 چنین کدی می‌تواند به وضعیت‌های نامشخص منجر شود. بنابراین محدودیت‌هایی برای استفاده از مقادیر تعریف‌نشده برای [IShape::set_Frame](../../ishape/set_frame/) اضافه شده است. مقادیر x، y، width، height، flipH، flipV و rotationAngle باید تعریف شوند (نه std::numeric_limits<float>::quiet_NaN() یا [NullableBool::NotDefined](../../nullablebool/)). کد نمونه بالا اکنون استثنای ArgumentException را پرتاب می‌کند. این موارد برای موارد استفاده زیر اعمال می‌شود:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // نمی‌تواند نامشخص باشد

SharedPtr<IShapeCollection> shapes = ...;
// پارامترهای x، y، width، height نمی‌توانند std::numeric_limits<float>::quiet_NaN() باشند:
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

اما چارچوب برای متد [IShape::set_RawFrame](../../ishape/set_rawframe/) می‌تواند تعریف‌نشده باشد. این وقتی معقول است که شکل به یک جای‌دار لینک شود. سپس مقادیر چارچوب شکل تعریف‌نشده از شکل جای‌دار والد بازنویسی می‌شوند. اگر برای آن شکل هیچ شکل جای‌دار والد وجود نداشته باشد، آن شکل از مقادیر پیش‌فرض استفاده می‌کند وقتی چارچوب مؤثر را بر اساس [IShape::get_RawFrame](../../ishape/get_rawframe/) خود ارزیابی می‌کند. مقادیر پیش‌فرض برای x، y، width، height، flipH، flipV و rotationAngle برابر 0 و [NullableBool::False](../../nullablebool/) هستند. برای مثال:
```cpp
SharedPtr<IShape> shape = ...; // شکل به جای‌دار لینک شده است
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // حالا شکل مقادیر x، y، height، flipH، flipV را از جای‌دار به ارث می‌برد و مقدار width=100 و rotationAngle=0 را بازنویسی می‌کند.
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IShapeFrame](../../ishapeframe/)
* کلاس [Shape](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)