---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides for C++ API 參考
description: 設定唯讀建議。寫入 bool.
type: docs
weight: 92
url: /zh-hant/aspose.slides/iprotectionmanager/set_readonlyrecommended/
---
## IProtectionManager::set_ReadOnlyRecommended(bool) 方法


設定唯讀建議。寫入 **bool**。

```cpp
virtual void Aspose::Slides::IProtectionManager::set_ReadOnlyRecommended(bool value)=0
```

## 備註



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## 另見

* 類別 [IProtectionManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)