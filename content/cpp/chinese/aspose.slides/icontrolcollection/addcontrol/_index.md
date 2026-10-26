---
title: AddControl()
second_title: Aspose.Slides C++ API 参考
description: 创建并将新控件添加到集合中。
type: docs
weight: 53
url: /zh/aspose.slides/icontrolcollection/addcontrol/
---
## IControlCollection::AddControl(ControlType, float, float, float, float) 方法

创建并将新控件添加到集合中。

```cpp
virtual System::SharedPtr<IControl> Aspose::Slides::IControlCollection::AddControl(ControlType controlType, float x, float y, float width, float height)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| controlType | [ControlType](../../controltype/) | 要添加的控件类型。 |
| x | **float** | 形状框左侧的X坐标。 |
| y | **float** | 形状框顶部的Y坐标。 |
| width | **float** | 形状框的宽度。 |
| height | **float** | 形状框的高度。 |

### 返回值

已创建的控件 [IControl](../../icontrol/)。

## 另请参阅

* Enum [ControlType](../../controltype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IControl](../../icontrol/)
* Class [IControlCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)