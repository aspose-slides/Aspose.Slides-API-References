---
title: set_RawFrame()
second_title: Aspose.Slides for C++ API 參考
description: 設定原始形狀框架的屬性。寫入 IShapeFrame.
type: docs
weight: 53
url: /zh-hant/aspose.slides/ishape/set_rawframe/
---
## IShape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) 方法

設定原始形狀框架的屬性。寫入 [IShapeFrame](../../ishapeframe/).

```cpp
virtual void Aspose::Slides::IShape::set_RawFrame(System::SharedPtr<IShapeFrame> value)=0
```

## 備註

嘗試將未定義的框架指派給 [IShape::set_Frame](../set_frame/) 的程式碼在一般情況下是沒有意義的（尤其在父 [GroupShape](../../groupshape/) 多層嵌套於其他 GroupShape 時）。例如：
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
此類程式碼可能導致不明的情況。因此已針對 [IShape::set_Frame](../set_frame/) 使用未定義值加入限制。x、y、width、height、flipH、flipV 以及 rotationAngle 必須被定義（不能是 std::numeric_limits<float>::quiet_NaN() 或 [NullableBool::NotDefined](../../nullablebool/)）。上述範例程式碼現在會拋出 ArgumentException 例外。此規則適用於以下使用情境：
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // 不能為未定義

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

但是 [IShape::set_RawFrame](./) 方法的框架可以是未定義的。當形狀連結至佔位符時，這是合理的。此時未定義的形狀框架值會從父佔位符形狀覆寫。如果該形狀沒有父佔位符形狀，則該形狀會在根據其 [IShape::get_RawFrame](../get_rawframe/) 評估有效框架時使用預設值。x、y、width、height、flipH、flipV 以及 rotationAngle 的預設值分別為 0 和 [NullableBool::False](../../nullablebool/)。例如：
```cpp
SharedPtr<IShape> shape = ...; // shape 已連結到佔位符
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // 現在 shape 繼承佔位符的 x、y、height、flipH、flipV 值，並覆寫 width=100 與 rotationAngle=0.
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IShapeFrame](../../ishapeframe/)
* 類別 [IShape](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)