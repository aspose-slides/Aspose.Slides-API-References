---
title: init_font_scheme_from method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.theme/overridetheme/init_font_scheme_from/
weight: 70
---
## init_font_scheme_from(self, font_scheme) {#ifontscheme}
使用新对象初始化 FontScheme，以覆盖 InheritedTheme 的 FontScheme。


```python
def init_font_scheme_from(self, font_scheme):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_scheme | [`IFontScheme`](/slides/python-net/zh/aspose.slides.theme/ifontscheme) | 用于初始化的数据。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 如果 FontScheme 已经被初始化（非 None），则抛出此异常。 |
| **RuntimeError(Proxy error(ArgumentNullException))** | 如果 fontScheme 参数为 None，则抛出此异常。 |



### 参见
* 类 [`IFontScheme`](/slides/python-net/zh/aspose.slides.theme/ifontscheme)
* 类 [`OverrideTheme`](/slides/python-net/zh/aspose.slides.theme/overridetheme)
* 模块 [`aspose.slides.theme`](/slides/python-net/zh/aspose.slides.theme)
* 库 [`Aspose.Slides`](/slides/python-net)