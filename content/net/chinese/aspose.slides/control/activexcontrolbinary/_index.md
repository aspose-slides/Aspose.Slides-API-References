---
title: ActiveXControlBinary
second_title: Aspose.Sildes for .NET API Reference
description: 指定当用于持久化的方法为 PersistStream、PersistStreamInit 或 PersistStorage 时 ActiveX 控件的持久性。
type: docs
weight: 10
url: /zh/aspose.slides/control/activexcontrolbinary/
---

## Control.ActiveXControlBinary 属性

指定当用于持久化的方法为 PersistStream、PersistStreamInit 或 PersistStorage 时 ActiveX 控件的持久性。

```csharp
public byte[] ActiveXControlBinary { get; }
```

### 示例

下一个示例演示了使用 ActiveXControlBinary 属性来更改 ActiveX 属性：

```csharp
[C#]
if (control.Persistence == PersistenceType.PersistPropertyBag)
{
    control.Properties["Value"] = value;
}
else
{
    YourMethodHere(control.ActiveXControlBinary); //使用您自己的方法来管理存储在其二进制文件中的 ActiveX 属性
}
```

### 参见

* class [Control](../../control)
* namespace [Aspose.Slides](../../control)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->