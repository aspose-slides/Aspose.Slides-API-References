---
title: CheckPassword()
second_title: Aspose.Slides C++ API 参考
description: 检查对使用打开密码保护的演示文稿，密码是否正确。
type: docs
weight: 53
url: /zh/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) 方法

检查对使用打开密码保护的演示文稿，密码是否正确。

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 要检查的密码。 |

### 返回值

如果演示文稿受打开密码保护且密码正确则返回 true，否则返回 false。

## 备注

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

当密码为 null 或空字符串时，此方法返回 false。 

## 参见

* 类 [String](../../../system/string/)
* 类 [IPresentationInfo](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)