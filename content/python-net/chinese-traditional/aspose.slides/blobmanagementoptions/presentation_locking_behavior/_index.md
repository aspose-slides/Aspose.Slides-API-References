---
title: presentation_locking_behavior property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/blobmanagementoptions/presentation_locking_behavior/
weight: 40
---
## presentation_locking_behavior 屬性
此屬性定義 Presentation 類別的實例在其生命週期內是否可以成為來源（檔案
或串流）的擁有者。若實例為擁有者，則會鎖定來源。這有助於在處理 BLOB 時提升記憶體使用與效能，但在 Presentation 實例的生命週期內，來源（串流或檔案）無法變更。

### 定義：
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```

### 參見
* 類別 [`BlobManagementOptions`](/slides/python-net/zh-hant/aspose.slides/blobmanagementoptions)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)