---
title: get_IsOnlyDocumentPropertiesLoaded()
second_title: Aspose.Slides for C++ API 參考
description: 此屬性在簡報檔案受密碼保護且此檔案的文件屬性為公開時才有意義。 true 值表示僅在未使用密碼的情況下從加密的簡報檔案中載入文件屬性。 false 值表示使用正確的密碼載入整個加密的簡報，而不僅載入文件屬性。如果簡報未加密，則屬性值始終為 false。如果加密檔案的文件屬性不是公開的，則屬性值始終為 false。如果 PresentationEx.EncryptDocumentProperties 為 true，則 IsOnlyDocumentPropertiesLoaded 屬性值始終為 false。 只讀 bool.
type: docs
weight: 40
url: /zh-hant/aspose.slides/iprotectionmanager/get_isonlydocumentpropertiesloaded/
---
## IProtectionManager::get_IsOnlyDocumentPropertiesLoaded() 方法


此屬性在簡報檔案受密碼保護且此檔案的文件屬性為公開時有意義。 true 值表示僅從未使用密碼的加密簡報檔案中載入文件屬性。 false 值表示使用正確密碼載入整個加密簡報，而不僅僅載入文件屬性。 如果簡報未加密，則屬性值始終為 false。 如果加密檔案的文件屬性不是公開的，則屬性值始終為 false。 如果 PresentationEx.EncryptDocumentProperties 為 true，則 IsOnlyDocumentPropertiesLoaded 屬性值始終為 false。 只讀 **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_IsOnlyDocumentPropertiesLoaded()=0
```

## 參見

* 類別 [IProtectionManager](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)