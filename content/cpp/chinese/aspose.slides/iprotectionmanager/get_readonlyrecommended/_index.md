---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides C++ API 参考
description: 获取只读推荐。读取 bool。
type: docs
weight: 79
url: /zh/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() 方法


获取只读推荐。读取 **bool**。

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
```

## 备注



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## 另见

* 类 [IProtectionManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)