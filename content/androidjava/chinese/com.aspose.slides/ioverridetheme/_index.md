---
title: IOverrideTheme
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个覆盖主题。
type: docs
url: /zh/com.aspose.slides/ioverridetheme/
---
**所有实现的接口：**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

表示一个覆盖主题。

## 方法

| 方法 | 描述 |
| --- | --- |
| [isEmpty()](#isEmpty--) | True 值表示 ColorScheme、FontScheme、FormatScheme 为 null，且任何使用此主题对象的覆盖都会被禁用。 |
| [initColorScheme()](#initColorScheme--) | 使用新对象初始化 ColorScheme，以覆盖 InheritedTheme 的 ColorScheme。 |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | 使用新对象初始化 ColorScheme，以覆盖 InheritedTheme 的 ColorScheme。 |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | 使用新对象初始化 ColorScheme，以覆盖 InheritedTheme 的 ColorScheme。 |
| [initFontScheme()](#initFontScheme--) | 使用新对象初始化 FontScheme，以覆盖 InheritedTheme 的 FontScheme。 |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | 使用新对象初始化 FontScheme，以覆盖 InheritedTheme 的 FontScheme。 |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | 使用新对象初始化 FontScheme，以覆盖 InheritedTheme 的 FontScheme。 |
| [initFormatScheme()](#initFormatScheme--) | 使用新对象初始化 FormatScheme，以覆盖 InheritedTheme 的 FormatScheme。 |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | 使用新对象初始化 FormatScheme，以覆盖 InheritedTheme 的 FormatScheme。 |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | 使用新对象初始化 FormatScheme，以覆盖 InheritedTheme 的 FormatScheme。 |
| [clear()](#clear--) | 将 ColorScheme、FontScheme、FormatScheme 设置为 null，以禁用此主题对象的任何覆盖。 |

### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

True 值表示 ColorScheme、FontScheme、FormatScheme 为 null，且任何使用此主题对象的覆盖都会被禁用。只读 boolean.

**返回值：**
boolean

### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

使用新对象初始化 ColorScheme，以覆盖 InheritedTheme 的 ColorScheme。

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

使用新对象初始化 ColorScheme，以覆盖 InheritedTheme 的 ColorScheme。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | 用于初始化的数据。 |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

使用新对象初始化 ColorScheme，以覆盖 InheritedTheme 的 ColorScheme。并使用 InheritedTheme 的 ColorScheme 数据初始化此新对象。

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

使用新对象初始化 FontScheme，以覆盖 InheritedTheme 的 FontScheme。

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

使用新对象初始化 FontScheme，以覆盖 InheritedTheme 的 FontScheme。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | 用于初始化的数据。 |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

使用新对象初始化 FontScheme，以覆盖 InheritedTheme 的 FontScheme。并使用 InheritedTheme 的 FontScheme 数据初始化此新对象。

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

使用新对象初始化 FormatScheme，以覆盖 InheritedTheme 的 FormatScheme。

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

使用新对象初始化 FormatScheme，以覆盖 InheritedTheme 的 FormatScheme。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | 用于初始化的数据。 |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

使用新对象初始化 FormatScheme，以覆盖 InheritedTheme 的 FormatScheme。并使用 InheritedTheme 的 FormatScheme 数据初始化此新对象。

### clear() {#clear--}
```
public abstract void clear()
```

将 ColorScheme、FontScheme、FormatScheme 设置为 null，以禁用此主题对象的任何覆盖。