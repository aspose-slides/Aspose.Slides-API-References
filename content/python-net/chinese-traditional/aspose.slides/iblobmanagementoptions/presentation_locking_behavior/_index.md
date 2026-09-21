---
title: presentation_locking_behavior property
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/
weight: 30
---
## presentation_locking_behavior 屬性
此屬性定義 Presentation 類別的實例是否可以成為來源 - 檔案 
            或 串流 在實例的生命週期內。若實例是擁有者，則鎖定來源。這有助於 
            改善記憶體消耗與效能，同時處理 BLOB 時，但來源（串流或檔案） 
            無法在 Presentation 的實例生命週期內變更。這是一個範例：

### 定義：
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```

### 另請參閱
* 類別 [`IBlobManagementOptions`](/slides/python-net/zh-hant/aspose.slides/iblobmanagementoptions)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)