---
title: set_RawFrame()
second_title: Aspose.Slides برای C++ مرجع API
description: ویژگی‌های فریم خام شکل را تنظیم می‌کند. IShapeFrame را بنویسید.
type: docs
weight: 53
url: /fa/aspose.slides/shape/set_rawframe/
---
## Shape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) متد

Sets the raw shape frame's properties. Write [IShapeFrame](../../ishapeframe/).

```cpp
void Aspose::Slides::Shape::set_RawFrame(System::SharedPtr<IShapeFrame> value) override
```

## توضیحات

Code that attempts to assign undefined frame to [IShape::set_Frame](../../ishape/set_frame/) doesn't make sense in general case (particulary in case when parent [GroupShape](../../groupshape/) is multiple nested into other GroupShape-s). For example: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
 or 
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
 Such code can lead to unclear situations. So restrictions had been added for using undefined values for [IShape::set_Frame](../../ishape/set_frame/). Values of x, y, width, height, flipH, flipV and rotationAngle must be defined (not std::numeric_limits<float>::quiet_NaN() or [NullableBool::NotDefined](../../nullablebool/)). Example code above now throws ArgumentException exception. This applies to these use cases: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // نمی‌تواند تعریف نشده باشد

SharedPtr<IShapeCollection> shapes = ...;
// پارامترهای x، y، width، height نمی‌توانند برابر std::numeric_limits<float>::quiet_NaN() باشند:
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

But a frame for [IShape::set_RawFrame](../../ishape/set_rawframe/) method can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its [IShape::get_RawFrame](../../ishape/get_rawframe/). Default values are 0 and [NullableBool::False](../../nullablebool/) for x, y, width, height, flipH, flipV and rotationAngle. For example: 
```cpp
SharedPtr<IShape> shape = ...; // شکل به placeholder پیوند خورده است
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // اکنون شکل مقادیر x، y، height، flipH، flipV را از placeholder به ارث می‌برد و مقدار width=100 و rotationAngle=0 را بازنویسی می‌کند.
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IShapeFrame](../../ishapeframe/)
* کلاس [Shape](../)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)