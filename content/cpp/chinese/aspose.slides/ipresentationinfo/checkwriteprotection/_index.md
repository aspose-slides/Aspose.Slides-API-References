---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API 参考
description: 检查用于修改的密码是否正确，以验证受写保护的演示文稿。
type: docs
weight: 66
url: /zh/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) 方法


检查用于修改的密码是否正确，以验证受写保护的演示文稿。

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 要检查的密码。 |

### 返回值

如果演示文稿受写保护且密码正确，则返回 True；否则返回 False。
## 备注



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```



1. 在调用此方法之前，您应检查 [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) 属性。
1. 当 password 为 null 或为空时，此方法返回 false。



## 另见

* 类 [String](../../../system/string/)
* 类 [IPresentationInfo](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)