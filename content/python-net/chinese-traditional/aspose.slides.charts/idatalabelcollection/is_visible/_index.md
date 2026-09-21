---
title: is_visible property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/idatalabelcollection/is_visible/
weight: 120
---
## is_visible 屬性
False 表示資料標籤預設為不可見 (且所有 Show*-flags (ShowValue, ...) 的 DefaultDataLabelFormat 屬性皆為 false)。只讀 **bool**.

### 備註

如果資料標籤預設為可見，您可以使用 Hide() 方法將其預設隱藏。
但是如果資料標籤預設為不可見 (IsVisible 為 false)，您可以透過設定 Show*-flags (ShowValue, ...) 的 DefaultDataLabelFormat 屬性為 true 狀態，使資料標籤「預設可見」。

### 定義:
```python
@property
def is_visible(self):
    ...
```

### 參見
* 類別 [`IDataLabelCollection`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelcollection)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)