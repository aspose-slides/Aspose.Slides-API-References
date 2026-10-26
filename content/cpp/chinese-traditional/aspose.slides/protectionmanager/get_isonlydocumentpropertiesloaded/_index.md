---
title: get_IsOnlyDocumentPropertiesLoaded()
second_title: Aspose.Slides for C++ API 參考
description: 此屬性在簡報檔案受密碼保護且該檔案的文件屬性為公開時才有意義。值為 true 表示僅在不使用密碼的情況下從加密的簡報檔案中載入文件屬性。值為 false 表示會使用正確的密碼載入整個加密的簡報，而不僅載入文件屬性。如果簡報未加密，則屬性值始終為 false。如果加密檔案的文件屬性不是公開的，則屬性值始終為 false。如果 Presentation.EncryptDocumentProperties 為 true，則 IsOnlyDocumentPropertiesLoaded 屬性值始終為 false。唯讀 bool.
type: docs
weight: 40
url: /zh-hant/aspose.slides/protectionmanager/get_isonlydocumentpropertiesloaded/
---
## ProtectionManager::get_IsOnlyDocumentPropertiesLoaded() 方法

此屬性在簡報檔案受密碼保護且該檔案的文件屬性為公開時才有意義。值為 true 表示僅從加密的簡報檔案中載入文件屬性，且不使用密碼。值為 false 表示會使用正確的密碼載入整個加密的簡報，而不僅載入文件屬性。如果簡報未加密，則屬性值永遠為 false。如果加密檔案的文件屬性不是公開的，則屬性值永遠為 false。如果 Presentation.EncryptDocumentProperties 為 true，則 IsOnlyDocumentPropertiesLoaded 屬性值永遠為 false。唯讀 **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_IsOnlyDocumentPropertiesLoaded() override
```

## 參見

* 類別 [ProtectionManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)