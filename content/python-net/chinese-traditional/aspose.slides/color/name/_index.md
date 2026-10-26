---
title: name property
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/color/name/
weight: 190
---
## 名稱屬性
取得此顏色的名稱。<br/>            對於具名顏色（例如 `Color.red` 這樣的具名常數，或使用 [`from_name`](/slides/python-net/zh-hant/aspose.slides/color/from_name/) 建立的顏色），會返回 .NET 名稱，例如 `"Red"` 或 `"LightBlue"`。<br/>            對於其他任何顏色，會返回不帶前導零的小寫十六進位 ARGB 值，例如 `"ffff0000"`。 `Color.empty.name` 為 `"0"`。
            唯讀 **str**。

### 定義:
```python
@property
def name(self):
    ...
```


### 另請參考
* 類別 [`Color`](/slides/python-net/zh-hant/aspose.slides/color)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)