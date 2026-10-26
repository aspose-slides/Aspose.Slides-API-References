---
title: init_color_scheme_from method
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.theme/overridetheme/init_color_scheme_from/
weight: 40
---
## init_color_scheme_from(self, color_scheme) {#icolorscheme}
使用新物件初始化 ColorScheme，以覆寫 InheritedTheme 的 ColorScheme。

```python
def init_color_scheme_from(self, color_scheme):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| color_scheme | [`IColorScheme`](/slides/python-net/zh-hant/aspose.slides.theme/icolorscheme) | 用於初始化的資料。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 如果 ColorScheme 已經初始化（非 None），則拋出此例外。 |
| **RuntimeError(Proxy error(ArgumentNullException))** | 如果 colorScheme 參數為 None，則拋出此例外。 |

### 另請參閱
* 類別 [`IColorScheme`](/slides/python-net/zh-hant/aspose.slides.theme/icolorscheme)
* 類別 [`OverrideTheme`](/slides/python-net/zh-hant/aspose.slides.theme/overridetheme)
* 模組 [`aspose.slides.theme`](/slides/python-net/zh-hant/aspose.slides.theme)
* 函式庫 [`Aspose.Slides`](/slides/python-net)