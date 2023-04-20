---
title: get_RawFrame()
second_title: Aspose.Slides for C++ API Reference
description: Returns the raw shape frame's properties. Read IShapeFrame.
type: docs
weight: 40
url: /cpp/aspose.slides/ishape/get_rawframe/
---
## IShape::get_RawFrame() method


Returns the raw shape frame's properties. Read [IShapeFrame](../../ishapeframe/).

```cpp
virtual System::SharedPtr<IShapeFrame> Aspose::Slides::IShape::get_RawFrame()=0
```

## Remarks


Code that attempts to assign undefined frame to [IShape::set_Frame](../set_frame/) doesn't make sense in general case (particulary in case when parent [GroupShape](../../groupshape/) is multiple nested into other GroupShape-s). For example: 
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
 Such code can lead to unclear situations. So restrictions had been added for using undefined values for [IShape::set_Frame](../set_frame/). Values of x, y, width, height, flipH, flipV and rotationAngle must be defined (not std::numeric_limits<float>::quiet_NaN() or [NullableBool::NotDefined](../../nullablebool/)). Example code above now throws ArgumentException exception. This applies to these use cases: 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // cannot be undefined

SharedPtr<IShapeCollection> shapes = ...;
// x, y, width, height parameters cannot be std::numeric_limits<float>::quiet_NaN():
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


But a frame for [IShape::set_RawFrame](../set_rawframe/) method can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its [IShape::get_RawFrame](./). Default values are 0 and [NullableBool::False](../../nullablebool/) for x, y, width, height, flipH, flipV and rotationAngle. For example: 
```cpp
SharedPtr<IShape> shape = ...; // shape is linked to placeholder
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShapeFrame](../../ishapeframe/)
* Class [IShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)