---
title: CheckWriteProtection()
second_title: Aspose.Slides for C++ API 参考
description: 确定演示文稿是否受到密码保护以进行修改。
type: docs
weight: 157
url: /zh/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) 方法

确定演示文稿是否受到密码保护以进行修改。

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 用于检查的密码。 |

### 返回值

如果密码有效则返回 True；否则返回 false。

## 备注

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. 在调用此方法之前，您应该检查 [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) 属性。
1. 当密码为 null 或为空时，此方法返回 false。

## 另见

* 类 [String](../../../system/string/)
* 类 [ProtectionManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)