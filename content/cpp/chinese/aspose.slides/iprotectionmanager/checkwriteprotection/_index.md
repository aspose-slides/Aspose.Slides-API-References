---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API 参考
description: 确定演示文稿是否受密码保护以进行修改。
type: docs
weight: 157
url: /zh/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) method

确定演示文稿是否被密码保护以修改。

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 用于检查的密码。 |

### 返回值

True if the password is valid; otherwise, false.

## 备注

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. 在调用此方法之前，您应检查 [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) 属性。
1. 当密码为 null 或空时，此方法返回 false。

## 另请参见

* 类 [String](../../../system/string/)
* 类 [IProtectionManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)