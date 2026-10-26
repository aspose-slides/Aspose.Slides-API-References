---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides C++ API 参考
description: 获取只读建议。读取 bool.
type: docs
weight: 79
url: /zh/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() 方法

获取只读建议。读取 **bool**。

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
```

## 备注

下面的示例代码演示了如何使用 [Aspose.Slides](../../) 在 C# 中将 PowerPoint [Presentation](../../presentation/) 设置为只读。

```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## 另见

* 类 [ProtectionManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)