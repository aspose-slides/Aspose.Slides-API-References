---
title: from_known_color method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
根據指定的預先定義顏色建立顏色。<br/>這是取得系統顏色（例如 `KnownColor.CONTROL`）的唯一方式：系統顏色不會以 `Color` 屬性公開，因為其值取決於桌面佈景主題，故從函式庫執行階段讀取。

### 傳回值

此方法建立的顏色。



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| known_color | **KnownColor** | `KnownColor` 列舉的元素（鏡像 .NET `System.Drawing.KnownColor` 的 `IntEnum`）或其整數值。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **ValueError** | 該值不是有效的 `KnownColor` 成員。 |



### 另見
* 類別 [`Color`](/slides/python-net/zh-hant/aspose.slides/color)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)