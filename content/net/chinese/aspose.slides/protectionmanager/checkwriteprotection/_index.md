---
title: CheckWriteProtection
second_title: Aspose.Sildes for .NET API Reference
description: 确定演示文稿是否有密码保护以进行修改。
type: docs
weight: 70
url: /zh/aspose.slides/protectionmanager/checkwriteprotection/
---

## ProtectionManager.CheckWriteProtection 方法

确定演示文稿是否有密码保护以进行修改。

```csharp
public bool CheckWriteProtection(string password)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| password | String | 用于检查的密码。 |

### 返回值

如果密码有效，则为真；否则，为假。

### 注意事项

1. 在调用此方法之前，您应检查 [`IsWriteProtected`](../iswriteprotected) 属性。 2. 当密码为 null 或空时，此方法返回假。

### 示例

```csharp
[C#]
using (var presentation = new Presentation(presentationFilePath))
{
    var isWriteProtected = presentation.ProtectionManager.CheckWriteProtection("my_password");
}
```

### 另见

* class [ProtectionManager](../../protectionmanager)
* namespace [Aspose.Slides](../../protectionmanager)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->