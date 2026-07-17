---
title: CheckPassword()
second_title: Aspose.Slides for C++ API 参考
description: 检查受开放密码保护的演示文稿的密码是否正确。
type: docs
weight: 53
url: /zh/aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo::CheckPassword(System::String) 方法

检查受开放密码保护的演示文稿的密码是否正确。

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 要检查的密码。 |

### 返回值

如果演示文稿受开放密码保护且密码正确则返回 true，否则返回 false。

## 备注

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

当密码为 null 或为空时，此方法返回 false。

## 另见

* 类 [String](../../../system/string/)
* 类 [PresentationInfo](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)