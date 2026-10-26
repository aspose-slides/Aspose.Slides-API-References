---
title: get_substitutions method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ifontsmanager/get_substitutions/
weight: 60
---
## get_substitutions(self) {#}
取得有關在簡報渲染時將被替換的字型資訊。

### 回傳

所有字型替換的集合 [`FontSubstitutionInfo`](/slides/python-net/zh-hant/aspose.slides/fontsubstitutioninfo)。

```python
def get_substitutions(self):
    ...
```



## get_substitutions(self, slides) {#listint}
取得有關在指定投影片渲染期間將被替換的字型資訊。

### 回傳

指定投影片的所有字型替換集合 ([`FontSubstitutionInfo`](/slides/python-net/zh-hant/aspose.slides/fontsubstitutioninfo))。

```python
def get_substitutions(self, slides):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| slides | **List[int]** | 用於檢索字型替換資訊的投影片索引陣列，起始值為 1。 |

### 另見
* 類別 [`FontSubstitutionInfo`](/slides/python-net/zh-hant/aspose.slides/fontsubstitutioninfo)
* 類別 [`IFontsManager`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)