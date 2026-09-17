---
title: init_format_scheme_from method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.theme/ioverridetheme/init_format_scheme_from/
weight: 100
---
## init_format_scheme_from(self, format_scheme) {#iformatscheme}
使用新对象初始化 FormatScheme，以覆盖 InheritedTheme 的 FormatScheme。


```python
def init_format_scheme_from(self, format_scheme):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| format_scheme | [`IFormatScheme`](/slides/python-net/zh/aspose.slides.theme/iformatscheme) | 用于初始化的数据。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 如果 FormatScheme 已经初始化（非 None），则抛出此异常。 |
| **RuntimeError(Proxy error(ArgumentNullException))** | 如果 formatScheme 参数为 None，则抛出此异常。 |



### 参见
* 类 [`IFormatScheme`](/slides/python-net/zh/aspose.slides.theme/iformatscheme)
* 类 [`IOverrideTheme`](/slides/python-net/zh/aspose.slides.theme/ioverridetheme)
* 模块 [`aspose.slides.theme`](/slides/python-net/zh/aspose.slides.theme)
* 库 [`Aspose.Slides`](/slides/python-net)