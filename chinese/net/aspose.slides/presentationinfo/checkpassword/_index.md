---
title: CheckPassword
second_title: Aspose.Slides for .NET API 参考
description: 检查受开放密码保护的演示文稿的密码是否正确
type: docs
weight: 50
url: /zh/net/aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo.CheckPassword method

检查受开放密码保护的演示文稿的密码是否正确。

```csharp
public bool CheckPassword(string password)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| password | String | 要检查的密码。 |

### 返回值

如果演示文稿受开放密码保护并且密码正确，则为真，否则为假。

### 评论

当密码为空或为空时，该方法返回false。

### 例子

```csharp
[C#]
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo(presentationFilePath);
bool isPasswordCorrect = info.CheckPassword("my_password");
```

### 也可以看看

* class [PresentationInfo](../../presentationinfo)
* 命名空间 [Aspose.Slides](../../presentationinfo)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->