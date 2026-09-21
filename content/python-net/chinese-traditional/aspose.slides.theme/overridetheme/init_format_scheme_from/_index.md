---
title: init_format_scheme_from method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.theme/overridetheme/init_format_scheme_from/
weight: 100
---
## init_format_scheme_from(self, format_scheme) {#iformatscheme}
使用新物件初始化 FormatScheme，以覆寫 InheritedTheme 的 FormatScheme。


```python
def init_format_scheme_from(self, format_scheme):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| format_scheme | [`IFormatScheme`](/slides/python-net/zh-hant/aspose.slides.theme/iformatscheme) | 用於初始化的資料。 |

### 例外情況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 如果 FormatScheme 已經被初始化（非 None），則拋出此錯誤。 |
| **RuntimeError(Proxy error(ArgumentNullException))** | 如果 formatScheme 參數為 None，則拋出此錯誤。 |



### 參見
* 類別 [`IFormatScheme`](/slides/python-net/zh-hant/aspose.slides.theme/iformatscheme)
* 類別 [`OverrideTheme`](/slides/python-net/zh-hant/aspose.slides.theme/overridetheme)
* 模組 [`aspose.slides.theme`](/slides/python-net/zh-hant/aspose.slides.theme)
* 函式庫 [`Aspose.Slides`](/slides/python-net)