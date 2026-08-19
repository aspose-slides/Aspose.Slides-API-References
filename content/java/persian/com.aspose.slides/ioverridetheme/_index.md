---
title: IOverrideTheme
second_title: مستندات API Aspose.Slides برای Java
description: نمایش یک تم حاکم.
type: docs
url: /fa/com.aspose.slides/ioverridetheme/
---
**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

نمایش یک تم حاکم.
## متدها

| متد | توضیح |
| --- | --- |
| [isEmpty()](#isEmpty--) | مقدار true به این معناست که ColorScheme، FontScheme، FormatScheme برابر null هستند و هر گونه حاکمیتی با این شی تم غیرفعال می‌شود. |
| [initColorScheme()](#initColorScheme--) | مقداردهی اولیه ColorScheme با شی جدید برای حاکمیت ColorScheme از InheritedTheme. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | مقداردهی اولیه ColorScheme با شی جدید برای حاکمیت ColorScheme از InheritedTheme. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | مقداردهی اولیه ColorScheme با شی جدید برای حاکمیت ColorScheme از InheritedTheme. |
| [initFontScheme()](#initFontScheme--) | مقداردهی اولیه FontScheme با شی جدید برای حاکمیت FontScheme از InheritedTheme. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | مقداردهی اولیه FontScheme با شی جدید برای حاکمیت FontScheme از InheritedTheme. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | مقداردهی اولیه FontScheme با شی جدید برای حاکمیت FontScheme از InheritedTheme. |
| [initFormatScheme()](#initFormatScheme--) | مقداردهی اولیه FormatScheme با شی جدید برای حاکمیت FormatScheme از InheritedTheme. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | مقداردهی اولیه FormatScheme با شی جدید برای حاکمیت FormatScheme از InheritedTheme. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | مقداردهی اولیه FormatScheme با شی جدید برای حاکمیت FormatScheme از InheritedTheme. |
| [clear()](#clear--) | تنظیم ColorScheme، FontScheme، FormatScheme به null برای غیرفعال کردن هر حاکمیتی با این شی تم. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

مقدار true به این معناست که ColorScheme، FontScheme، FormatScheme برابر null هستند و هر گونه حاکمیتی با این شی تم غیرفعال می‌شود. بولی فقط‌خواندنی.

**باز می‌گرداند:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

مقداردهی اولیه ColorScheme با شی جدید برای حاکمیت ColorScheme از InheritedTheme.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

مقداردهی اولیه ColorScheme با شی جدید برای حاکمیت ColorScheme از InheritedTheme.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | داده برای مقداردهی اولیه. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

مقداردهی اولیه ColorScheme با شی جدید برای حاکمیت ColorScheme از InheritedTheme. و داده‌های این شی جدید را با داده‌های ColorScheme از InheritedTheme مقداردهی می‌کند.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

مقداردهی اولیه FontScheme با شی جدید برای حاکمیت FontScheme از InheritedTheme.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

مقداردهی اولیه FontScheme با شی جدید برای حاکمیت FontScheme از InheritedTheme.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | داده برای مقداردهی اولیه. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

مقداردهی اولیه FontScheme با شی جدید برای حاکمیت FontScheme از InheritedTheme. و داده‌های این شی جدید را با داده‌های FontScheme از InheritedTheme مقداردهی می‌کند.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

مقداردهی اولیه FormatScheme با شی جدید برای حاکمیت FormatScheme از InheritedTheme.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

مقداردهی اولیه FormatScheme با شی جدید برای حاکمیت FormatScheme از InheritedTheme.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | داده برای مقداردهی اولیه. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

مقداردهی اولیه FormatScheme با شی جدید برای حاکمیت FormatScheme از InheritedTheme. و داده‌های این شی جدید را با داده‌های FormatScheme از InheritedTheme مقداردهی می‌کند.

### clear() {#clear--}
```
public abstract void clear()
```

تنظیم ColorScheme، FontScheme، FormatScheme به null برای غیرفعال کردن هر حاکمیتی با این شی تم.