---
title: is_visible property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/datalabelcollection/is_visible/
weight: 120
---
## is_visible 屬性
False 表示資料標籤預設為不可見 (因此 DefaultDataLabelFormat 屬性的所有 Show*-flags (ShowValue, ...) 為 false)。唯讀 **bool**.

### 備註
如果資料標籤預設為可見，您可以使用 Hide() 方法將其預設設為隱藏。 但如果資料標籤預設不可見 (IsVisible 為 false)，您可以透過設定 DefaultDataLabelFormat 屬性的 Show*-flags (ShowValue, ...) 為 true 狀態，使資料標籤 "預設可見"。

### 定義：
```python
@property
def is_visible(self):
    ...
```

### 另見
* 類別 [`DataLabelCollection`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelcollection)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)