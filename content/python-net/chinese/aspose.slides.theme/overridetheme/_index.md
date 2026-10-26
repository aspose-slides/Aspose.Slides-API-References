---
title: OverrideTheme class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.theme/overridetheme/
---
## OverrideTheme 类

表示一个覆盖主题。

**继承:**[`OverrideTheme`](/slides/python-net/zh/aspose.slides.theme/overridetheme) → [`Theme`](/slides/python-net/zh/aspose.slides.theme/theme)

OverrideTheme 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`color_scheme`](/slides/python-net/zh/aspose.slides.theme/overridetheme/color_scheme/) | 返回颜色方案。<br/>            只读 [`IColorScheme`](/slides/python-net/zh/aspose.slides.theme/icolorscheme)。 |
| [`font_scheme`](/slides/python-net/zh/aspose.slides.theme/overridetheme/font_scheme/) | 返回字体方案。<br/>            只读 [`IFontScheme`](/slides/python-net/zh/aspose.slides.theme/ifontscheme)。 |
| [`format_scheme`](/slides/python-net/zh/aspose.slides.theme/overridetheme/format_scheme/) | 返回形状格式方案。<br/>            只读 [`IFormatScheme`](/slides/python-net/zh/aspose.slides.theme/iformatscheme)。 |
| [`presentation`](/slides/python-net/zh/aspose.slides.theme/overridetheme/presentation/) | 返回父演示文稿。<br/>            只读 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation)。 |
| [`is_empty`](/slides/python-net/zh/aspose.slides.theme/overridetheme/is_empty/) | True 值表示 ColorScheme、FontScheme、FormatScheme 为 None，且使用此主题对象的任何覆盖都已禁用。<br/>            只读 **bool**。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/zh/aspose.slides.theme/overridetheme/get_effective/#) | 获取应用继承后的有效主题数据。 |
| [`init_color_scheme(self)`](/slides/python-net/zh/aspose.slides.theme/overridetheme/init_color_scheme/#) | 使用新对象初始化 ColorScheme，以覆盖 InheritedTheme 的 ColorScheme。 |
| [`init_color_scheme_from(self, color_scheme)`](/slides/python-net/zh/aspose.slides.theme/overridetheme/init_color_scheme_from/#icolorscheme) | 使用新对象初始化 ColorScheme，以覆盖 InheritedTheme 的 ColorScheme。 |
| [`init_color_scheme_from_inherited(self)`](/slides/python-net/zh/aspose.slides.theme/overridetheme/init_color_scheme_from_inherited/#) | 使用新对象初始化 ColorScheme，以覆盖 InheritedTheme 的 ColorScheme。并用 InheritedTheme 的 ColorScheme 数据初始化此新对象的数据。 |
| [`init_font_scheme(self)`](/slides/python-net/zh/aspose.slides.theme/overridetheme/init_font_scheme/#) | 使用新对象初始化 FontScheme，以覆盖 InheritedTheme 的 FontScheme。 |
| [`init_font_scheme_from(self, font_scheme)`](/slides/python-net/zh/aspose.slides.theme/overridetheme/init_font_scheme_from/#ifontscheme) | 使用新对象初始化 FontScheme，以覆盖 InheritedTheme 的 FontScheme。 |
| [`init_font_scheme_from_inherited(self)`](/slides/python-net/zh/aspose.slides.theme/overridetheme/init_font_scheme_from_inherited/#) | 使用新对象初始化 FontScheme，以覆盖 InheritedTheme 的 FontScheme。并用 InheritedTheme 的 FontScheme 数据初始化此新对象的数据。 |
| [`init_format_scheme(self)`](/slides/python-net/zh/aspose.slides.theme/overridetheme/init_format_scheme/#) | 使用新对象初始化 FormatScheme，以覆盖 InheritedTheme 的 FormatScheme。 |
| [`init_format_scheme_from(self, format_scheme)`](/slides/python-net/zh/aspose.slides.theme/overridetheme/init_format_scheme_from/#iformatscheme) | 使用新对象初始化 FormatScheme，以覆盖 InheritedTheme 的 FormatScheme。 |
| [`init_format_scheme_from_inherited(self)`](/slides/python-net/zh/aspose.slides.theme/overridetheme/init_format_scheme_from_inherited/#) | 使用新对象初始化 FormatScheme，以覆盖 InheritedTheme 的 FormatScheme。并用 InheritedTheme 的 FormatScheme 数据初始化此新对象的数据。 |
| [`clear(self)`](/slides/python-net/zh/aspose.slides.theme/overridetheme/clear/#) | 将 ColorScheme、FontScheme、FormatScheme 设置为 None，以禁用此主题对象的任何覆盖。 |

### 另请参见
* 类 [`OverrideTheme`](/slides/python-net/zh/aspose.slides.theme/overridetheme)
* 类 [`Theme`](/slides/python-net/zh/aspose.slides.theme/theme)
* 模块 [`aspose.slides.theme`](/slides/python-net/zh/aspose.slides.theme)
* 库 [`Aspose.Slides`](/slides/python-net)