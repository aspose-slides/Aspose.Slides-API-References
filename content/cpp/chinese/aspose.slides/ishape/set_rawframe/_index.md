---
title: set_RawFrame()
second_title: Aspose.Slides for C++ API 参考
description: 设置原始形状框的属性。写入 IShapeFrame.
type: docs
weight: 53
url: /zh/aspose.slides/ishape/set_rawframe/
---
## IShape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) 方法

设置原始形状框的属性。写入 [IShapeFrame](../../ishapeframe/)。

```cpp
virtual void Aspose::Slides::IShape::set_RawFrame(System::SharedPtr<IShapeFrame> value)=0
```

## 备注

尝试将未定义的框分配给 [IShape::set_Frame](../set_frame/) 的代码在一般情况下没有意义（尤其是在父 [GroupShape](../../groupshape/) 被多个其他 GroupShape 嵌套的情况下）。例如： 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
或
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
此类代码可能导致不明确的情况。因此已添加限制，以防在 [IShape::set_Frame](../set_frame/) 中使用未定义的值。x、y、width、height、flipH、flipV 和 rotationAngle 的值必须已定义（不能是 std::numeric_limits<float>::quiet_NaN() 或 [NullableBool::NotDefined](../../nullablebool/)）。上述示例代码现在会抛出 ArgumentException 异常。这适用于以下使用情况： 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // 不能为未定义

SharedPtr<IShapeCollection> shapes = ...;
// x、y、width、height 参数不能是 std::numeric_limits<float>::quiet_NaN():
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

但是，对于 [IShape::set_RawFrame](./) 方法的框可以是未定义的。当形状链接到占位符时这是有意义的。此时未定义的形状框值会从父占位符形状中覆盖。如果该形状没有父占位符形状，则在根据其 [IShape::get_RawFrame](../get_rawframe/) 计算有效框时，该形状会使用默认值。x、y、width、height、flipH、flipV 和 rotationAngle 的默认值为 0 和 [NullableBool::False](../../nullablebool/)。例如： 
```cpp
SharedPtr<IShape> shape = ...; // shape 已链接到占位符
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // 现在 shape 从占位符继承 x、y、height、flipH、flipV 的值，并覆盖 width=100 和 rotationAngle=0.
```

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IShapeFrame](../../ishapeframe/)
* 类 [IShape](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)