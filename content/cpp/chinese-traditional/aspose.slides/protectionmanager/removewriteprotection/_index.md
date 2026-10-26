---
title: RemoveWriteProtection()
second_title: Aspose.Slides for C++ API 參考文件
description: 移除此簡報的寫入保護。
type: docs
weight: 144
url: /zh-hant/aspose.slides/protectionmanager/removewriteprotection/
---
## ProtectionManager::RemoveWriteProtection() 方法


移除此簡報的寫入保護。

```cpp
void Aspose::Slides::ProtectionManager::RemoveWriteProtection() override
```

## 備註


此範例程式碼示範如何從 PowerPoint [Presentation](../../presentation/) 中移除寫入保護。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->RemoveWriteProtection();
presentation->Save(u"write-protection-removed.pptx", SaveFormat::Pptx);
```

## 另請參閱

* 類別 [ProtectionManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)