---
title: OverrideTheme
second_title: Aspose.Slides for Android via Java API 參考文件
description: 表示一個覆寫的佈景主題。
type: docs
url: /zh-hant/com.aspose.slides/overridetheme/
---
**繼承：**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**所有已實作的介面：**
[com.aspose.slides.IOverrideTheme](../../com.aspose.slides/ioverridetheme)
```
public final class OverrideTheme extends Theme implements IOverrideTheme
```

表示一個覆寫的佈景主題。
## 方法

| 方法 | 說明 |
| --- | --- |
| [initColorScheme()](#initColorScheme--) | 初始化 ColorScheme，使用新物件以覆寫 InheritedTheme 的 ColorScheme。 |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | 初始化 ColorScheme，使用新物件以覆寫 InheritedTheme 的 ColorScheme。 |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | 初始化 ColorScheme，使用新物件以覆寫 InheritedTheme 的 ColorScheme。 |
| [initFontScheme()](#initFontScheme--) | 初始化 FontScheme，使用新物件以覆寫 InheritedTheme 的 FontScheme。 |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | 初始化 FontScheme，使用新物件以覆寫 InheritedTheme 的 FontScheme。 |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | 初始化 FontScheme，使用新物件以覆寫 InheritedTheme 的 FontScheme。 |
| [initFormatScheme()](#initFormatScheme--) | 初始化 FormatScheme，使用新物件以覆寫 InheritedTheme 的 FormatScheme。 |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | 初始化 FormatScheme，使用新物件以覆寫 InheritedTheme 的 FormatScheme。 |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | 初始化 FormatScheme，使用新物件以覆寫 InheritedTheme 的 FormatScheme。 |
| [getColorScheme()](#getColorScheme--) | 返回顏色方案。 |
| [getFontScheme()](#getFontScheme--) | 返回字型方案。 |
| [getFormatScheme()](#getFormatScheme--) | 返回形狀格式方案。 |
| [isEmpty()](#isEmpty--) | True 值表示 ColorScheme、FontScheme、FormatScheme 為 null，且任何使用此佈景主題物件的覆寫皆已停用。 |
| [clear()](#clear--) | 將 ColorScheme、FontScheme、FormatScheme 設為 null，以停用任何使用此佈景主題物件的覆寫。 |
| [getVersion()](#getVersion--) |  |
### initColorScheme() {#initColorScheme--}
```
public final void initColorScheme()
```

初始化 ColorScheme，使用新物件以覆寫 InheritedTheme 的 ColorScheme。

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public final void initColorSchemeFrom(IColorScheme colorScheme)
```

初始化 ColorScheme，使用新物件以覆寫 InheritedTheme 的 ColorScheme。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | 用於初始化的資料。 |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public final void initColorSchemeFromInherited()
```

初始化 ColorScheme，使用新物件以覆寫 InheritedTheme 的 ColorScheme。並以 InheritedTheme 的 ColorScheme 資料初始化此新物件。

### initFontScheme() {#initFontScheme--}
```
public final void initFontScheme()
```

初始化 FontScheme，使用新物件以覆寫 InheritedTheme 的 FontScheme。

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public final void initFontSchemeFrom(IFontScheme fontScheme)
```

初始化 FontScheme，使用新物件以覆寫 InheritedTheme 的 FontScheme。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | 用於初始化的資料。 |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public final void initFontSchemeFromInherited()
```

初始化 FontScheme，使用新物件以覆寫 InheritedTheme 的 FontScheme。並以 InheritedTheme 的 FontScheme 資料初始化此新物件。

### initFormatScheme() {#initFormatScheme--}
```
public final void initFormatScheme()
```

初始化 FormatScheme，使用新物件以覆寫 InheritedTheme 的 FormatScheme。

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public final void initFormatSchemeFrom(IFormatScheme formatScheme)
```

初始化 FormatScheme，使用新物件以覆寫 InheritedTheme 的 FormatScheme。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | 用於初始化的資料。 |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public final void initFormatSchemeFromInherited()
```

初始化 FormatScheme，使用新物件以覆寫 InheritedTheme 的 FormatScheme。並以 InheritedTheme 的 FormatScheme 資料初始化此新物件。

### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```

返回顏色方案。唯讀 [IColorScheme](../../com.aspose.slides/icolorscheme)。

**返回：**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```

返回字型方案。唯讀 [IFontScheme](../../com.aspose.slides/ifontscheme)。

**返回：**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

返回形狀格式方案。唯讀 [IFormatScheme](../../com.aspose.slides/iformatscheme)。

**返回：**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```

True 值表示 ColorScheme、FontScheme、FormatScheme 為 null，且任何使用此佈景主題物件的覆寫皆已停用。唯讀布林值。

**返回：**
boolean
### clear() {#clear--}
```
public final void clear()
```

將 ColorScheme、FontScheme、FormatScheme 設為 null，以停用任何使用此佈景主題物件的覆寫。

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**返回：**
long