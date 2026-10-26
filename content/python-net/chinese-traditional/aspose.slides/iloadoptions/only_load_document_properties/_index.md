---
title: only_load_document_properties property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/iloadoptions/only_load_document_properties/
weight: 100
---
## only_load_document_properties 屬性
如果簡報檔案受密碼保護，此屬性才有意義。
            值為 true 表示只能從加密的簡報檔案載入文件屬性，且必須忽略密碼。
            值為 false 表示必須使用正確的密碼載入整個加密的簡報。
            如果簡報未加密，則屬性值將永遠被忽略。
            如果加密檔案的文件屬性不是公開的且屬性值為 true，則無法載入文件屬性，並會拋出例外。
            可讀寫 **bool**。

### 定義：
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```


### 另請參閱
* 類別 [`ILoadOptions`](/slides/python-net/zh-hant/aspose.slides/iloadoptions)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)