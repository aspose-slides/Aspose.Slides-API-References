---
title: Encrypt()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定密码加密演示文稿。
type: docs
weight: 105
url: /zh/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) 方法

使用指定的密码加密[Presentation](../../presentation/)。

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | 密码。 |

## 备注

以下示例代码演示如何加密 PowerPoint [Presentation](../../presentation/)。
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## 另见

* 类 [String](../../../system/string/)
* 类 [ProtectionManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)