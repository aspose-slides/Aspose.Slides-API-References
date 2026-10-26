---
title: IOverrideTheme
second_title: Aspose.Slides for Java API 参考
description: 表示一个覆盖主题。
type: docs
url: /zh/com.aspose.slides/ioverridetheme/
---
**All Implemented Interfaces:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

表示一个覆盖主题。
## 方法

| Method | Description |
| --- | --- |
| [isEmpty()](#isEmpty--) | True 值表示 ColorScheme、FontScheme、FormatScheme 为 null，且任何对该主题对象的覆盖都已禁用。 |
| [initColorScheme()](#initColorScheme--) | 使用新的对象初始化 ColorScheme，以覆盖 InheritedTheme 的 ColorScheme。 |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | 使用新的对象初始化 ColorScheme，以覆盖 InheritedTheme 的 ColorScheme。 |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | 使用新的对象初始化 ColorScheme，以覆盖 InheritedTheme 的 ColorScheme。 |
| [initFontScheme()](#initFontScheme--) | 使用新的对象初始化 FontScheme，以覆盖 InheritedTheme 的 FontScheme。 |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | 使用新的对象初始化 FontScheme，以覆盖 InheritedTheme 的 FontScheme。 |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | 使用新的对象初始化 FontScheme，以覆盖 InheritedTheme 的 FontScheme。 |
| [initFormatScheme()](#initFormatScheme--) | 使用新的对象初始化 FormatScheme，以覆盖 InheritedTheme 的 FormatScheme。 |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | 使用新的对象初始化 FormatScheme，以覆盖 InheritedTheme 的 FormatScheme。 |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | 使用新的对象初始化 FormatScheme，以覆盖 InheritedTheme 的 FormatScheme。 |
| [clear()](#clear--) | 将 ColorScheme、FontScheme、FormatScheme 设置为 null，以禁用对该主题对象的任何覆盖。 |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

True 值表示 ColorScheme、FontScheme、FormatScheme 为 null，且任何对该主题对象的覆盖都已禁用。只读布尔值。

**Returns:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

使用新的对象初始化 ColorScheme，以覆盖 InheritedTheme 的 ColorScheme。

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

使用新的对象初始化 ColorScheme，以覆盖 InheritedTheme 的 ColorScheme。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | 用于初始化的数据。 |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

使用新的对象初始化 ColorScheme，以覆盖 InheritedTheme 的 ColorScheme。并使用 InheritedTheme 的 ColorScheme 数据来初始化此新对象的数据。

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

使用新的对象初始化 FontScheme，以覆盖 InheritedTheme 的 FontScheme。

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

使用新的对象初始化 FontScheme，以覆盖 InheritedTheme 的 FontScheme。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | 用于初始化的数据。 |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

使用新的对象初始化 FontScheme，以覆盖 InheritedTheme 的 FontScheme。并使用 InheritedTheme 的 FontScheme 数据来初始化此新对象的数据。

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

使用新的对象初始化 FormatScheme，以覆盖 InheritedTheme 的 FormatScheme。

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

使用新的对象初始化 FormatScheme，以覆盖 InheritedTheme 的 FormatScheme。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | 用于初始化的数据。 |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

使用新的对象初始化 FormatScheme，以覆盖 InheritedTheme 的 FormatScheme。并使用 InheritedTheme 的 FormatScheme 数据来初始化此新对象的数据。

### clear() {#clear--}
```
public abstract void clear()
```

将 ColorScheme、FontScheme、FormatScheme 设置为 null，以禁用对该主题对象的任何覆盖。