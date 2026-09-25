---
title: from_name method
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
根據指定的預定義顏色名稱建立顏色。<br/>查找不區分大小寫，且會忽略底線和空格：`"LightBlue"`、`"lightblue"` 和 `"light_blue"` 都會解析為 `Color.light_blue`。請參閱 [`Color`](/slides/python-net/zh-hant/aspose.slides/color) 類別頁面以取得預定義顏色的清單。

### 回傳值

已命名的顏色。

```python
@staticmethod
def from_name(name):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| name | **str** | 字串，表示預定義顏色的名稱。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **ValueError** | 此名稱不是預定義顏色的名稱。 |
| **TypeError** | 此名稱不是字串。 |

### 另見
* 類別 [`Color`](/slides/python-net/zh-hant/aspose.slides/color)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)