---
title: only_load_document_properties property
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/loadoptions/only_load_document_properties/
weight: 110
---
## only_load_document_properties 屬性
            如果簡報檔案受密碼保護，此屬性才有意義。
            值為 true 表示只需從加密的簡報檔案中載入文件屬性，且忽略密碼。
            值為 false 表示必須使用正確的密碼載入整個加密的簡報。
            如果簡報未加密，則屬性值將始終被忽略。
            如果加密檔案的文件屬性不是公開的且屬性值為 true，則無法載入文件屬性，並會拋出例外。
            讀/寫 **bool**。

### 定義:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```


### 參見
* 類別 [`LoadOptions`](/slides/python-net/zh-hant/aspose.slides/loadoptions)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)