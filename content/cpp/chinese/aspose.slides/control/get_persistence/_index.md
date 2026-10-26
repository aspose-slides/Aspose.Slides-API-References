---
title: get_Persistence()
second_title: Aspose.Slides C++ API 参考
description: 获取用于存储 ActiveX 控件属性的方法。只读 PersistenceType。
type: docs
weight: 1
url: /zh/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() 方法

获取用于存储 ActiveX 控件属性的方法。只读 [PersistenceType](../../persistencetype/)。

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## 备注

下面的示例演示了使用 Persistence 属性来检查 ActiveX 对象的属性是否可能被更改为基于 XML 的 ActiveX 属性：

```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // 使用您自己的方法管理存储在其二进制文件中的 ActiveX 属性
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## 另请参阅

* 枚举 [PersistenceType](../../persistencetype/)
* 类 [Control](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)