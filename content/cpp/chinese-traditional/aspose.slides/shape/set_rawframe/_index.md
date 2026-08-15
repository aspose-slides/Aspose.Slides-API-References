---
title: set_RawFrame()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定原始形狀框架的屬性。寫入 IShapeFrame.
type: docs
weight: 53
url: /zh-hant/aspose.slides/shape/set_rawframe/
---
## Shape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) method

設定原始形狀框架的屬性。寫入 [IShapeFrame](../../ishapeframe/)。

```cpp
void Aspose::Slides::Shape::set_RawFrame(System::SharedPtr<IShapeFrame> value) override
```

## 備註

嘗試將未定義的框架指派給 [IShape::set_Frame](../../ishape/set_frame/) 的程式碼在一般情況下沒有意義（特別是當父項 [GroupShape](../../groupshape/) 多層嵌套於其他 GroupShape-s）。例如： 
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
 此類程式碼可能導致不清楚的情況。因此已加入限制，禁止對 [IShape::set_Frame](../../ishape/set_frame/) 使用未定義的值。x、y、width、height、flipH、flipV 與 rotationAngle 必須被定義（不能是 std::numeric_limits<float>::quiet_NaN() 或 [NullableBool::NotDefined](../../nullablebool/)）。上述範例程式碼現在會拋出 ArgumentException 例外。此規則適用於以下使用情況： 
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

但是 [IShape::set_RawFrame](../../ishape/set_rawframe/) 方法的框架可以是未定義的。當形狀連結到佔位符時，這是合理的。此時未定義的形狀框架值會從父佔位符形狀覆寫。若該形狀沒有父佔位符形狀，則該形狀會在根據其 [IShape::get_RawFrame](../../ishape/get_rawframe/) 計算有效框架時使用預設值。x、y、width、height、flipH、flipV 與 rotationAngle 的預設值分別為 0 和 [NullableBool::False](../../nullablebool/)。例如： 
```cpp
SharedPtr<IShape> shape = ...; // shape 已連結到佔位符
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // 現在 shape 從佔位符繼承 x、y、height、flipH、flipV 的值，並將 width=100 與 rotationAngle=0 覆寫。
```

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IShapeFrame](../../ishapeframe/)
* 類別 [Shape](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)