---
title: get_ActiveXControlBinary()
second_title: Aspose.Slides for C++ API 参考
description: 指定在持久化方法为 PersistStream、PersistStreamInit 或 PersistStorage 时，ActiveX 控件的持久化方式。
type: docs
weight: 118
url: /zh/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() 方法

指定在持久化方法为 PersistStream、PersistStreamInit 或 PersistStorage 时，ActiveX 控件的持久化方式。

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## 备注

下面的示例展示了使用 ActiveXControlBinary 属性来更改 ActiveX 属性：

```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // 使用您自己的方法来管理存储在其二进制文件中的 ActiveX 属性
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [Control](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)