---
title: set_RawFrame()
second_title: Aspose.Slides برای C++ مرجع API
description: ویژگی‌های قاب شکل خام را تنظیم می‌کند. IShapeFrame را بنویسید.
type: docs
weight: 53
url: /fa/aspose.slides/ishape/set_rawframe/
---
## IShape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) متد

ویژگی‌های قاب شکل خام را تنظیم می‌کند. [IShapeFrame](../../ishapeframe/).

```cpp
virtual void Aspose::Slides::IShape::set_RawFrame(System::SharedPtr<IShapeFrame> value)=0
```

## ملاحظات

کدی که سعی می‌کند قاب نامتعین را به [IShape::set_Frame](../set_frame/) اختصاص دهد، در حالت کلی منطقی نیست (به‌ویژه در موردی که والد [GroupShape](../../groupshape/) به‌صورت تو در تو در چندین GroupShape قرار دارد). برای مثال:
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
 چنین کدی می‌تواند به وضعیت‌های نامشخص منجر شود. بنابراین محدودیت‌هایی برای استفاده از مقادیر نامتعین برای [IShape::set_Frame](../set_frame/) اضافه شده است. مقادیر x، y، width، height، flipH، flipV و rotationAngle باید تعریف شوند (نه std::numeric_limits<float>::quiet_NaN() یا [NullableBool::NotDefined](../../nullablebool/)). کد مثال بالا اکنون استثنای ArgumentException را پرتاب می‌کند. این موارد برای موارد استفاده زیر اعمال می‌شود:
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

اما قاب برای متد [IShape::set_RawFrame](./) می‌تواند نامتعین باشد. این منطقی است زمانی که شکل به یک placeholder پیوند خورده باشد. سپس مقادیر نامعنون قاب شکل از placeholder والد بازنویسی می‌شود. اگر برای آن شکل placeholder والد وجود نداشته باشد، شکل مقادیر پیش‌فرض را هنگام ارزیابی قاب مؤثر بر اساس [IShape::get_RawFrame](../get_rawframe/) خود استفاده می‌کند. مقادیر پیش‌فرض برای x، y، width، height، flipH، flipV و rotationAngle برابر 0 و [NullableBool::False](../../nullablebool/) هستند. برای مثال:
```cpp
SharedPtr<IShape> shape = ...; // شکل به placeholder پیوند خورده است
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // اکنون شکل مقادیر x، y، height، flipH، flipV را از placeholder ارث می‌برد و width=100 و rotationAngle=0 را بازنویسی می‌کند.
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShapeFrame](../../ishapeframe/)
* Class [IShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)