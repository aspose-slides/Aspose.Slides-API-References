---
title: AddControl()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立並將新控制項加入集合。
type: docs
weight: 53
url: /zh-hant/aspose.slides/icontrolcollection/addcontrol/
---
## IControlCollection::AddControl(ControlType, float, float, float, float) 方法

建立並將新控制項加入集合。

```cpp
virtual System::SharedPtr<IControl> Aspose::Slides::IControlCollection::AddControl(ControlType controlType, float x, float y, float width, float height)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| controlType | [ControlType](../../controltype/) | 要加入的控制項類型。 |
| x | **float** | 形狀框架左側的 X 坐標。 |
| y | **float** | 形狀框架頂部的 Y 坐標。 |
| width | **float** | 形狀框架的寬度。 |
| height | **float** | 形狀框架的高度。 |

### 回傳值

已建立的控制項 [IControl](../../icontrol/)。

## 另請參閱

* 列舉 [ControlType](../../controltype/)
* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IControl](../../icontrol/)
* 類別 [IControlCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)