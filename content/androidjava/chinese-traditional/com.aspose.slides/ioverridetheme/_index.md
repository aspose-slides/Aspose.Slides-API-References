---
title: IOverrideTheme
second_title: Aspose.Slides for Android via Java API 參考
description: 代表一個覆寫的主題。
type: docs
url: /zh-hant/com.aspose.slides/ioverridetheme/
---
**所有已實作的介面：**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

代表一個覆寫的主題。

## 方法

| 方法 | 說明 |
| --- | --- |
| [isEmpty()](#isEmpty--) | True 值表示 ColorScheme、FontScheme、FormatScheme 為 null，且此主題物件的任何覆寫皆已停用。 |
| [initColorScheme()](#initColorScheme--) | 使用新物件初始化 ColorScheme 以覆寫 InheritedTheme 的 ColorScheme。 |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | 使用新物件初始化 ColorScheme 以覆寫 InheritedTheme 的 ColorScheme。 |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | 使用新物件初始化 ColorScheme 以覆寫 InheritedTheme 的 ColorScheme。 |
| [initFontScheme()](#initFontScheme--) | 使用新物件初始化 FontScheme 以覆寫 InheritedTheme 的 FontScheme。 |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | 使用新物件初始化 FontScheme 以覆寫 InheritedTheme 的 FontScheme。 |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | 使用新物件初始化 FontScheme 以覆寫 InheritedTheme 的 FontScheme。 |
| [initFormatScheme()](#initFormatScheme--) | 使用新物件初始化 FormatScheme 以覆寫 InheritedTheme 的 FormatScheme。 |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | 使用新物件初始化 FormatScheme 以覆寫 InheritedTheme 的 FormatScheme。 |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | 使用新物件初始化 FormatScheme 以覆寫 InheritedTheme 的 FormatScheme。 |
| [clear()](#clear--) | 將 ColorScheme、FontScheme、FormatScheme 設為 null，以停用此主題物件的任何覆寫。 |

### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

True 值表示 ColorScheme、FontScheme、FormatScheme 為 null，且此主題物件的任何覆寫皆已停用。唯讀 boolean。

**回傳:**
boolean

### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

使用新物件初始化 ColorScheme 以覆寫 InheritedTheme 的 ColorScheme。

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

使用新物件初始化 ColorScheme 以覆寫 InheritedTheme 的 ColorScheme。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | 用於初始化的資料。 |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

使用新物件初始化 ColorScheme 以覆寫 InheritedTheme 的 ColorScheme，並以 InheritedTheme 的 ColorScheme 資料初始化此新物件。

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

使用新物件初始化 FontScheme 以覆寫 InheritedTheme 的 FontScheme。

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

使用新物件初始化 FontScheme 以覆寫 InheritedTheme 的 FontScheme。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | 用於初始化的資料。 |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

使用新物件初始化 FontScheme 以覆寫 InheritedTheme 的 FontScheme，並以 InheritedTheme 的 FontScheme 資料初始化此新物件。

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

使用新物件初始化 FormatScheme 以覆寫 InheritedTheme 的 FormatScheme。

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

使用新物件初始化 FormatScheme 以覆寫 InheritedTheme 的 FormatScheme。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | 用於初始化的資料。 |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

使用新物件初始化 FormatScheme 以覆寫 InheritedTheme 的 FormatScheme，並以 InheritedTheme 的 FormatScheme 資料初始化此新物件。

### clear() {#clear--}
```
public abstract void clear()
```

將 ColorScheme、FontScheme、FormatScheme 設為 null，以停用此主題物件的任何覆寫。