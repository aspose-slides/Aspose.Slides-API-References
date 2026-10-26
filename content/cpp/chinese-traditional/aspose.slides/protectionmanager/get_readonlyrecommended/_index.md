---
title: get_ReadOnlyRecommended()
second_title: Aspose.Slides C++ API 參考
description: 取得唯讀建議。讀取 bool.
type: docs
weight: 79
url: /zh-hant/aspose.slides/protectionmanager/get_readonlyrecommended/
---
## ProtectionManager::get_ReadOnlyRecommended() 方法


取得唯讀建議。讀取 **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_ReadOnlyRecommended() override
```

## 備註


以下範例程式碼示範了如何使用 [Aspose.Slides](../../) 在 C# 中將 PowerPoint [Presentation](../../presentation/) 設定為唯讀。 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## 另請參閱

* 類別 [ProtectionManager](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)