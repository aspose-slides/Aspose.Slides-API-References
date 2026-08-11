---
title: get_RawFrame()
second_title: Aspose.Slides برای C++ مرجع API
description: خواص فریم خام شکل را برمی‌گرداند. IShapeFrame را بخوانید.
type: docs
weight: 40
url: /fa/aspose.slides/ishape/get_rawframe/
---
## IShape::get_RawFrame() متد

خواص فریم خام شکل را برمی‌گرداند. بخوانید [IShapeFrame](../../ishapeframe/).

```cpp
virtual System::SharedPtr<IShapeFrame> Aspose::Slides::IShape::get_RawFrame()=0
```

## توضیحات

کدی که سعی می‌کند فریم تعریف‌نشده را به [IShape::set_Frame](../set_frame/) اختصاص دهد، در حالت کلی معنادار نیست (به‌ویژه در حالتی که والد [GroupShape](../../groupshape/) به‌صورت چندگانه در GroupShape-های دیگر تو در تو باشد). برای مثال:
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
چنین کدی می‌تواند منجر به وضعیت‌های نامشخص شود. بنابراین محدودیت‌هایی برای استفاده از مقادیر تعریف‌نشده برای [IShape::set_Frame](../set_frame/) افزوده شد. مقادیر x، y، width، height، flipH، flipV و rotationAngle باید تعریف شوند (نه std::numeric_limits<float>::quiet_NaN() یا [NullableBool::NotDefined](../../nullablebool/)). کد مثال بالا اکنون استثنای ArgumentException را پرتاب می‌کند. این برای موارد استفاده زیر اعمال می‌شود:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // نمی‌تواند نامعین باشد

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

اما فریم برای متد [IShape::set_RawFrame](../set_rawframe/) می‌تواند تعریف‌نشده باشد. این زمانی منطقی است که شکل به یک جای‌دار لینک شده باشد. سپس مقادیر فریم تعریف‌نشده شکل از شکل جای‌دار والد بازنویسی می‌شوند. اگر برای آن شکل هیچ شکل جای‌دار والد وجود نداشته باشد، آن شکل از مقادیر پیش‌فرض استفاده می‌کند وقتی فریم مؤثر را بر اساس [IShape::get_RawFrame](./) خود ارزیابی می‌کند. مقادیر پیش‌فرض برای x، y، width، height، flipH، flipV و rotationAngle صفر و [NullableBool::False](../../nullablebool/) هستند. برای مثال:
```cpp
SharedPtr<IShape> shape = ...; // shape به placeholder لینک شده است
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // حالا shape مقادیر x, y, height, flipH, flipV را از placeholder به ارث می‌برد و width=100 و rotationAngle=0 را بازنویسی می‌کند.
```

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IShapeFrame](../../ishapeframe/)
* کلاس [IShape](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)