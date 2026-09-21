---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded 屬性
如果簡報檔案受密碼保護且該檔案的文件 
            屬性是公開的，此屬性才有意義。
            值為 true 表示僅從加密的 
            簡報檔案中載入文件屬性，且不需使用密碼。
            值為 false 表示使用正確的 
            密碼載入整個加密的簡報，而不僅載入文件屬性。
            如果簡報未加密，則屬性值始終為 false。
            如果加密檔案的文件屬性未公開，則屬性值始終為 false。
            如果 Presentation.EncryptDocumentProperties 為 true，則 IsOnlyDocumentPropertiesLoaded 
            屬性值始終為 false。
            唯讀 **bool**。

### 定義:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### 另見
* 類別 [`ProtectionManager`](/slides/python-net/zh-hant/aspose.slides/protectionmanager)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)