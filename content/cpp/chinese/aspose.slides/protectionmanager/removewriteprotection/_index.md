---
title: RemoveWriteProtection()
second_title: Aspose.Slides C++ API 参考
description: 移除此演示文稿的写保护。
type: docs
weight: 144
url: /zh/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() 方法

移除此演示文稿的写保护。

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## 备注

此示例代码展示了如何从 PowerPoint [Presentation](../../presentation/) 中移除写保护。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## 另请参见

* 类 [ProtectionManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)