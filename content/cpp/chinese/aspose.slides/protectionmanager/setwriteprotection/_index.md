---
title: SetWriteProtection()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的密码为此演示文稿设置写保护。
type: docs
weight: 131
url: /zh/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) 方法


为此演示文稿设置写保护，使用指定的密码。

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | 密码。 |
## 备注



以下示例代码演示了如何为演示文稿设置写保护。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [ProtectionManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)