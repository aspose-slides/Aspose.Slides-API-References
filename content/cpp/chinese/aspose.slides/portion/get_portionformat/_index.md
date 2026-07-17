---
title: get_PortionFormat()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个格式化对象，其中包含文本片段的显式设置的格式属性，未应用任何继承。只读 IPortionFormat。
type: docs
weight: 1
url: /zh/aspose.slides/portion/get_portionformat/
---
## Portion::get_PortionFormat() 方法

返回一个格式化对象，该对象包含文本片段的显式设置的格式属性，未应用任何继承。只读 [IPortionFormat](../../iportionformat/)。

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::Portion::get_PortionFormat() override
```

## 备注

格式化对象仅包含为当前片段定义的格式参数，未应用继承的数据。

若要获取包括继承在内的有效值，请使用 [PortionFormat::GetEffective](../../portionformat/geteffective/) 方法。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IPortionFormat](../../iportionformat/)
* 类 [Portion](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)