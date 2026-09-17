---
title: init_format_scheme_from method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.theme/overridetheme/init_format_scheme_from/
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
| format_scheme | [`IFormatScheme`](/slides/python-net/zh/aspose.slides.theme/iformatscheme) | 初始化所用的数据。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 当 FormatScheme 已经被初始化（非 None）时抛出。 |
| **RuntimeError(Proxy error(ArgumentNullException))** | 当 formatScheme 参数为 None 时抛出。 |

### 另请参见
* 类 [`IFormatScheme`](/slides/python-net/zh/aspose.slides.theme/iformatscheme)
* 类 [`OverrideTheme`](/slides/python-net/zh/aspose.slides.theme/overridetheme)
* 模块 [`aspose.slides.theme`](/slides/python-net/zh/aspose.slides.theme)
* 库 [`Aspose.Slides`](/slides/python-net)