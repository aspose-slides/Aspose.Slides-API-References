---
title: get_PortionFormat()
second_title: Aspose.Slides C++ API 参考
description: 返回格式对象，其中包含文本部分显式设置的格式属性，且未应用继承。只读 IPortionFormat。
type: docs
weight: 1
url: /zh/aspose.slides/iportion/get_portionformat/
---
## IPortion::get_PortionFormat() 方法


返回格式对象，其中包含文本部分显式设置的格式属性，且未应用继承。只读 [IPortionFormat](../../iportionformat/)。

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::IPortion::get_PortionFormat()=0
```

## 备注


该格式对象仅包含为当前部分定义的格式参数，未应用继承的数据。

要获取包括继承在内的有效值，请使用 [IPortionFormat::GetEffective](../../iportionformat/geteffective/) 方法。
## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IPortionFormat](../../iportionformat/)
* 类 [IPortion](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)