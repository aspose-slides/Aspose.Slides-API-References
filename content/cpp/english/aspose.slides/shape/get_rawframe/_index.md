---
title: get_RawFrame()
second_title: Aspose.Slides for C++ API Reference
description: Returns the raw shape frame's properties. Read IShapeFrame.
type: docs
weight: 40
url: /aspose.slides/shape/get_rawframe/
---
## Shape::get_RawFrame() method


Returns the raw shape frame's properties. Read [IShapeFrame](../../ishapeframe/).

```cpp
System::SharedPtr<IShapeFrame> Aspose::Slides::Shape::get_RawFrame() override
```

## Remarks


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


But a frame for [IShape::set_RawFrame](../../ishape/set_rawframe/) method can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its [IShape::get_RawFrame](../../ishape/get_rawframe/). Default values are 0 and [NullableBool::False](../../nullablebool/) for x, y, width, height, flipH, flipV and rotationAngle. For example: 
```cpp
SharedPtr<IShape> shape = ...; // shape is linked to placeholder
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShapeFrame](../../ishapeframe/)
* Class [Shape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)