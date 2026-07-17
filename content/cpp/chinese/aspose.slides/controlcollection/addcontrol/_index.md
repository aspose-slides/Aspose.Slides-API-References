---
title: AddControl()
second_title: Aspose.Slides for C++ API 参考
description: 创建并将新控件添加到集合中。
type: docs
weight: 40
url: /zh/aspose.slides/controlcollection/addcontrol/
---
## ControlCollection::AddControl(ControlType, float, float, float, float) 方法


创建并将新控件添加到集合中。

```cpp
System::SharedPtr<IControl> Aspose::Slides::ControlCollection::AddControl(ControlType controlType, float x, float y, float width, float height) override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| controlType | [ControlType](../../controltype/) | 要添加的控件类型。 |
| x | **float** | 形状框左侧的 X 坐标（**float**）。 |
| y | **float** | 形状框顶部的 Y 坐标（**float**）。 |
| width | **float** | 形状框的宽度（**float**）。 |
| height | **float** | 形状框的高度（**float**）。 |

### 返回值

已创建的控件。

## 另请参阅

* 枚举 [ControlType](../../controltype/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IControl](../../icontrol/)
* 类 [ControlCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)