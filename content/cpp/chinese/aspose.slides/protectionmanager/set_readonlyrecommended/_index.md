---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides C++ API 参考
description: 设置只读推荐。写入 bool。
type: docs
weight: 92
url: /zh/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) 方法


设置只读推荐。写入 **bool**.

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## 备注


下面的示例代码展示了如何在 C# 中使用 [Aspose.Slides](../../) 将 PowerPoint [Presentation](../../presentation/) 设置为只读。 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## 另请参阅

* 类 [ProtectionManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)