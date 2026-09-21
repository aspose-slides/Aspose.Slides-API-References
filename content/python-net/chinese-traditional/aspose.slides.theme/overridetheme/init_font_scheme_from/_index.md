---
title: init_font_scheme_from method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.theme/overridetheme/init_font_scheme_from/
weight: 70
---
## init_font_scheme_from(self, font_scheme) {#ifontscheme}
以新物件初始化 FontScheme，以覆寫 InheritedTheme 的 FontScheme。

```python
def init_font_scheme_from(self, font_scheme):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| font_scheme | [`IFontScheme`](/slides/python-net/zh-hant/aspose.slides.theme/ifontscheme) | 用於初始化的資料。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 如果 FontScheme 已經初始化（非 None），則拋出此例外。 |
| **RuntimeError(Proxy error(ArgumentNullException))** | 如果 fontScheme 參數為 None，則拋出此例外。 |

### 另請參考
* 類別 [`IFontScheme`](/slides/python-net/zh-hant/aspose.slides.theme/ifontscheme)
* 類別 [`OverrideTheme`](/slides/python-net/zh-hant/aspose.slides.theme/overridetheme)
* 模組 [`aspose.slides.theme`](/slides/python-net/zh-hant/aspose.slides.theme)
* 函式庫 [`Aspose.Slides`](/slides/python-net)