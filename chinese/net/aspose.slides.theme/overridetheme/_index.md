---
title: OverrideTheme
second_title: Aspose.Slides for .NET API 参考
description: 表示覆盖主题
type: docs
weight: 10650
url: /zh/net/aspose.slides.theme/overridetheme/
---
## OverrideTheme class

表示覆盖主题。

```csharp
public class OverrideTheme : Theme, IOverrideTheme
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [ColorScheme](../../aspose.slides.theme/overridetheme/colorscheme) { get; } | 返回配色方案。 只读[`IColorScheme`](../icolorscheme)。 |
| override [FontScheme](../../aspose.slides.theme/overridetheme/fontscheme) { get; } | 返回字体方案。 只读[`IFontScheme`](../ifontscheme)。 |
| override [FormatScheme](../../aspose.slides.theme/overridetheme/formatscheme) { get; } | 返回形状格式方案。 只读[`IFormatScheme`](../iformatscheme)。 |
| [IsEmpty](../../aspose.slides.theme/overridetheme/isempty) { get; } | True 值意味着 ColorScheme、FontScheme、FormatScheme 为 null，并且禁用了使用此主题对象的任何覆盖。 只读Boolean。 |
| [Presentation](../../aspose.slides.theme/theme/presentation) { get; } | 返回父演示文稿。 只读[`IPresentation`](../../aspose.slides/ipresentation)。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Clear](../../aspose.slides.theme/overridetheme/clear)() | 将 ColorScheme、FontScheme、FormatScheme 设置为 null 以禁用此主题对象的任何覆盖。 |
| [GetEffective](../../aspose.slides.theme/theme/geteffective)() | 获取应用了继承的有效主题数据。 |
| [InitColorScheme](../../aspose.slides.theme/overridetheme/initcolorscheme)() | 使用新对象初始化 ColorScheme，用于覆盖 InheritedTheme 的 ColorScheme。 |
| [InitColorSchemeFrom](../../aspose.slides.theme/overridetheme/initcolorschemefrom)(IColorScheme) | 使用新对象初始化 ColorScheme，用于覆盖 InheritedTheme 的 ColorScheme。 |
| [InitColorSchemeFromInherited](../../aspose.slides.theme/overridetheme/initcolorschemefrominherited)() | 使用新对象初始化 ColorScheme，用于覆盖 InheritedTheme 的 ColorScheme。并用 InheritedTheme 的 ColorScheme 的数据初始化这个新对象的数据。 |
| [InitFontScheme](../../aspose.slides.theme/overridetheme/initfontscheme)() | 使用新对象初始化 FontScheme，用于覆盖 InheritedTheme 的 FontScheme。 |
| [InitFontSchemeFrom](../../aspose.slides.theme/overridetheme/initfontschemefrom)(IFontScheme) | 使用新对象初始化 FontScheme，用于覆盖 InheritedTheme 的 FontScheme。 |
| [InitFontSchemeFromInherited](../../aspose.slides.theme/overridetheme/initfontschemefrominherited)() | 使用新对象初始化 FontScheme，用于覆盖 InheritedTheme 的 FontScheme。并用 InheritedTheme 的 FontScheme 的数据初始化这个新对象的数据。 |
| [InitFormatScheme](../../aspose.slides.theme/overridetheme/initformatscheme)() | 使用新对象初始化 FormatScheme，用于覆盖 InheritedTheme 的 FormatScheme。 |
| [InitFormatSchemeFrom](../../aspose.slides.theme/overridetheme/initformatschemefrom)(IFormatScheme) | 使用新对象初始化 FormatScheme，用于覆盖 InheritedTheme 的 FormatScheme。 |
| [InitFormatSchemeFromInherited](../../aspose.slides.theme/overridetheme/initformatschemefrominherited)() | 使用新对象初始化 FormatScheme，用于覆盖 InheritedTheme 的 FormatScheme。并用 InheritedTheme 的 FormatScheme 的数据初始化这个新对象的数据。 |

### 也可以看看

* class [Theme](../theme)
* interface [IOverrideTheme](../ioverridetheme)
* 命名空间 [Aspose.Slides.Theme](../../aspose.slides.theme)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->