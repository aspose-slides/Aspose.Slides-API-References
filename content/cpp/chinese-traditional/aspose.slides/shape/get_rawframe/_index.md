---
title: get_RawFrame()
second_title: Aspose.Slides for C++ API 參考
description: 傳回原始形狀框架的屬性。閱讀 IShapeFrame.
type: docs
weight: 40
url: /zh-hant/aspose.slides/shape/get_rawframe/
---
## Shape::get_RawFrame() 方法

傳回原始形狀框架的屬性。閱讀 [IShapeFrame](../../ishapeframe/)。

```cpp
System::SharedPtr<IShapeFrame> Aspose::Slides::Shape::get_RawFrame() override
```

## 備註

嘗試將未定義的框架指派給 [IShape::set_Frame](../../ishape/set_frame/) 的程式碼在一般情況下沒有意義（尤其是在父 [GroupShape](../../groupshape/) 多層嵌套於其他 GroupShape-s）。例如： 
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
 此類程式碼可能導致不明確的情況。因此已加入限制，不允許對 [IShape::set_Frame](../../ishape/set_frame/) 使用未定義的值。x、y、width、height、flipH、flipV 與 rotationAngle 的值必須被定義（不能是 std::numeric_limits<float>::quiet_NaN() 或 [NullableBool::NotDefined](../../nullablebool/)）。上方的範例程式碼現在會拋出 ArgumentException 例外。此限制適用於以下情況： 
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // 不能是未定義的

SharedPtr<IShapeCollection> shapes = ...;
// x、y、width、height 參數不能是 std::numeric_limits<float>::quiet_NaN():
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

但對於 [IShape::set_RawFrame](../../ishape/set_rawframe/) 方法而言，框架可以是未定義的。當形狀連結至佔位符時，這是合理的。此時未定義的形狀框架值會從父佔位符形狀中覆寫。如果該形狀沒有父佔位符形狀，則在根據其 [IShape::get_RawFrame](../../ishape/get_rawframe/) 計算有效框架時，該形狀會使用預設值。x、y、width、height、flipH、flipV 與 rotationAngle 的預設值分別為 0 與 [NullableBool::False](../../nullablebool/)。例如： 
```cpp
SharedPtr<IShape> shape = ...; // shape 已連結到佔位符
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // 現在 shape 繼承來自佔位符的 x、y、height、flipH、flipV 值，並覆寫 width=100 與 rotationAngle=0.
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IShapeFrame](../../ishapeframe/)
* 類別 [Shape](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)