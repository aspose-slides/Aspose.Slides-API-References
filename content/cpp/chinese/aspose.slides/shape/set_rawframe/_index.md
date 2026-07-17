---
title: set_RawFrame()
second_title: Aspose.Slides for C++ API 参考
description: 设置原始形状框架的属性。写入 IShapeFrame.
type: docs
weight: 53
url: /zh/aspose.slides/shape/set_rawframe/
---
## Shape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) 方法

设置原始形状框架的属性。写入 [IShapeFrame](../../ishapeframe/)。

```cpp
void Aspose::Slides::Shape::set_RawFrame(System::SharedPtr<IShapeFrame> value) override
```

## 备注

尝试将未定义的帧分配给 [IShape::set_Frame](../../ishape/set_frame/) 的代码在一般情况下没有意义（尤其是当父 [GroupShape](../../groupshape/) 多层嵌套到其他 GroupShape-s）。例如： 
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
此类代码可能导致不明确的情况。因此已为 [IShape::set_Frame](../../ishape/set_frame/) 添加了使用未定义值的限制。x、y、width、height、flipH、flipV 和 rotationAngle 的值必须被定义（不能是 std::numeric_limits<float>::quiet_NaN() 或 [NullableBool::NotDefined](../../nullablebool/)）。上述示例代码现在会抛出 ArgumentException 异常。这适用于以下使用情况： 
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

但 [IShape::set_RawFrame](../../ishape/set_rawframe/) 方法的框架可以是未定义的。当形状链接到占位符时，这有意义。随后未定义的形状框架值会从父占位符形状中覆盖。如果该形状没有父占位符形状，则该形状在基于其 [IShape::get_RawFrame](../../ishape/get_rawframe/) 评估有效框架时会使用默认值。默认值为 0 和 [NullableBool::False](../../nullablebool/)（用于 x、y、width、height、flipH、flipV 和 rotationAngle）。例如： 
```cpp
SharedPtr<IShape> shape = ...; // 形状已链接到占位符
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // 现在形状从占位符继承 x、y、height、flipH、flipV 的值，并将 width=100 和 rotationAngle=0 覆盖。
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IShapeFrame](../../ishapeframe/)
* 类 [Shape](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)