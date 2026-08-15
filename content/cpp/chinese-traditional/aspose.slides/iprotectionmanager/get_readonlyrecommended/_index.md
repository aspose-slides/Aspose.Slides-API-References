---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得唯讀建議。讀取 bool。
type: docs
weight: 79
url: /zh-hant/aspose.slides/iprotectionmanager/get_readonlyrecommended/
---
## IProtectionManager::get_ReadOnlyRecommended() 方法


取得唯讀建議。讀取 **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_ReadOnlyRecommended()=0
```

## 備註



```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## 另請參閱

* 類別 [IProtectionManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)