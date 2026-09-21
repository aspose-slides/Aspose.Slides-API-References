---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded 屬性
此屬性在簡報檔案受密碼保護且檔案的文件屬性為公開時才有意義。
值為 true 表示僅從加密的簡報檔案中載入文件屬性，且不需要使用密碼。
值為 false 表示使用正確的密碼載入整個加密的簡報，而不只是載入文件屬性。
如果簡報未加密，則屬性值始終為 false。
如果加密檔案的文件屬性不是公開的，則屬性值始終為 false。
如果 PresentationEx.EncryptDocumentProperties 為 true，則 IsOnlyDocumentPropertiesLoaded 屬性值始終為 false。
唯讀 **bool**。

### 定義:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### 另見
* 類別 [`IProtectionManager`](/slides/python-net/zh-hant/aspose.slides/iprotectionmanager)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)