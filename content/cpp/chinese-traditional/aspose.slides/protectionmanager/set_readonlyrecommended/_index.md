---
title: set_ReadOnlyRecommended()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定唯讀建議。寫入 bool.
type: docs
weight: 92
url: /zh-hant/aspose.slides/protectionmanager/set_readonlyrecommended/
---
## ProtectionManager::set_ReadOnlyRecommended(bool) 方法


設定唯讀建議。寫入 **bool**。

```cpp
void Aspose::Slides::ProtectionManager::set_ReadOnlyRecommended(bool value) override
```

## 備註


以下範例程式碼示範如何在 C# 中使用 [Aspose.Slides](../../) 將 PowerPoint [Presentation](../../presentation/) 設為唯讀。 
```cpp
auto pres = System::MakeObject<Presentation>();
pres->get_ProtectionManager()->set_ReadOnlyRecommended(true);
pres->Save(u"ReadOnlyPresentation.pptx", SaveFormat::Pptx);
```

## 參見

* 類別 [ProtectionManager](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)