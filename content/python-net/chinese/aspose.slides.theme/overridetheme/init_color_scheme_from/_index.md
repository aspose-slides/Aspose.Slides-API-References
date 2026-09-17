---
title: init_color_scheme_from method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.theme/overridetheme/init_color_scheme_from/
weight: 40
---
## init_color_scheme_from(self, color_scheme) {#icolorscheme}
使用新对象初始化 ColorScheme，以覆盖 InheritedTheme 的 ColorScheme。

```python
def init_color_scheme_from(self, color_scheme):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| color_scheme | [`IColorScheme`](/slides/python-net/zh/aspose.slides.theme/icolorscheme) | 用于初始化的数据。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 如果 ColorScheme 已经初始化（非 None），则抛出此异常。 |
| **RuntimeError(Proxy error(ArgumentNullException))** | 如果 colorScheme 参数为 None，则抛出此异常。 |

### 另请参阅
* 类 [`IColorScheme`](/slides/python-net/zh/aspose.slides.theme/icolorscheme)
* 类 [`OverrideTheme`](/slides/python-net/zh/aspose.slides.theme/overridetheme)
* 模块 [`aspose.slides.theme`](/slides/python-net/zh/aspose.slides.theme)
* 库 [`Aspose.Slides`](/slides/python-net)