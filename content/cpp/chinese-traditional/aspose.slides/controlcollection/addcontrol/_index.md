---
title: AddControl()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立並將新控制項加入集合。
type: docs
weight: 40
url: /zh-hant/aspose.slides/controlcollection/addcontrol/
---
## ControlCollection::AddControl(ControlType, float, float, float, float) 方法


建立並將新控制項加入集合。

```cpp
System::SharedPtr<IControl> Aspose::Slides::ControlCollection::AddControl(ControlType controlType, float x, float y, float width, float height) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| controlType | [ControlType](../../controltype/) | 要新增的控制項類型。 |
| x | **float** | 形狀框架左側的 X 座標。 |
| y | **float** | 形狀框架上側的 Y 座標。 |
| width | **float** | 形狀框架的寬度。 |
| height | **float** | 形狀框架的高度。 |

### 回傳值

已建立的控制項。

## 另見

* 列舉 [ControlType](../../controltype/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IControl](../../icontrol/)
* 類別 [ControlCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)