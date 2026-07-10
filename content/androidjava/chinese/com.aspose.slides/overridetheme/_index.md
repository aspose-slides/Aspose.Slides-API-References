---
title: OverrideTheme
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示一个覆盖主题。
type: docs
url: /zh/com.aspose.slides/overridetheme/
---
**继承:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**所有实现的接口:**
[com.aspose.slides.IOverrideTheme](../../com.aspose.slides/ioverridetheme)
```
public final class OverrideTheme extends Theme implements IOverrideTheme
```

表示一个覆盖主题。
## 方法

| 方法 | 描述 |
| --- | --- |
| [initColorScheme()](#initColorScheme--) | 使用新对象初始化 ColorScheme 以覆盖 InheritedTheme 的 ColorScheme。 |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | 使用新对象初始化 ColorScheme 以覆盖 InheritedTheme 的 ColorScheme。 |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | 使用新对象初始化 ColorScheme 以覆盖 InheritedTheme 的 ColorScheme。 |
| [initFontScheme()](#initFontScheme--) | 使用新对象初始化 FontScheme 以覆盖 InheritedTheme 的 FontScheme。 |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | 使用新对象初始化 FontScheme 以覆盖 InheritedTheme 的 FontScheme。 |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | 使用新对象初始化 FontScheme 以覆盖 InheritedTheme 的 FontScheme。 |
| [initFormatScheme()](#initFormatScheme--) | 使用新对象初始化 FormatScheme 以覆盖 InheritedTheme 的 FormatScheme。 |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | 使用新对象初始化 FormatScheme 以覆盖 InheritedTheme 的 FormatScheme。 |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | 使用新对象初始化 FormatScheme 以覆盖 InheritedTheme 的 FormatScheme。 |
| [getColorScheme()](#getColorScheme--) | 返回 ColorScheme。 |
| [getFontScheme()](#getFontScheme--) | 返回 FontScheme。 |
| [getFormatScheme()](#getFormatScheme--) | 返回形状格式方案。 |
| [isEmpty()](#isEmpty--) | True 值表示 ColorScheme、FontScheme、FormatScheme 为 null，且使用此主题对象的任何覆盖均已禁用。 |
| [clear()](#clear--) | 将 ColorScheme、FontScheme、FormatScheme 设为 null 以禁用使用此主题对象的任何覆盖。 |
| [getVersion()](#getVersion--) |  |

### initColorScheme() {#initColorScheme--}
```
public final void initColorScheme()
```

使用新对象初始化 ColorScheme 以覆盖 InheritedTheme 的 ColorScheme。

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public final void initColorSchemeFrom(IColorScheme colorScheme)
```

使用新对象初始化 ColorScheme 以覆盖 InheritedTheme 的 ColorScheme。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | 用于初始化的数据。 |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public final void initColorSchemeFromInherited()
```

使用新对象初始化 ColorScheme 以覆盖 InheritedTheme 的 ColorScheme。并使用 InheritedTheme 的 ColorScheme 数据初始化此新对象。

### initFontScheme() {#initFontScheme--}
```
public final void initFontScheme()
```

使用新对象初始化 FontScheme 以覆盖 InheritedTheme 的 FontScheme。

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public final void initFontSchemeFrom(IFontScheme fontScheme)
```

使用新对象初始化 FontScheme 以覆盖 InheritedTheme 的 FontScheme。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | 用于初始化的数据。 |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public final void initFontSchemeFromInherited()
```

使用新对象初始化 FontScheme 以覆盖 InheritedTheme 的 FontScheme。并使用 InheritedTheme 的 FontScheme 数据初始化此新对象。

### initFormatScheme() {#initFormatScheme--}
```
public final void initFormatScheme()
```

使用新对象初始化 FormatScheme 以覆盖 InheritedTheme 的 FormatScheme。

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public final void initFormatSchemeFrom(IFormatScheme formatScheme)
```

使用新对象初始化 FormatScheme 以覆盖 InheritedTheme 的 FormatScheme。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | 用于初始化的数据。 |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public final void initFormatSchemeFromInherited()
```

使用新对象初始化 FormatScheme 以覆盖 InheritedTheme 的 FormatScheme。并使用 InheritedTheme 的 FormatScheme 数据初始化此新对象。

### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```

返回 ColorScheme。只读 [IColorScheme](../../com.aspose.slides/icolorscheme)。

**返回值:**
[IColorScheme](../../com.aspose.slides/icolorscheme)

### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```

返回 FontScheme。只读 [IFontScheme](../../com.aspose.slides/ifontscheme)。

**返回值:**
[IFontScheme](../../com.aspose.slides/ifontscheme)

### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

返回形状格式方案。只读 [IFormatScheme](../../com.aspose.slides/iformatscheme)。

**返回值:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```

True 值表示 ColorScheme、FontScheme、FormatScheme 为 null，且使用此主题对象的任何覆盖均已禁用。只读 boolean。

**返回值:**
boolean

### clear() {#clear--}
```
public final void clear()
```

将 ColorScheme、FontScheme、FormatScheme 设为 null 以禁用使用此主题对象的任何覆盖。

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回值:**
long