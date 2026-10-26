---
title: IOverrideTheme
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک تم جایگزین‌کننده را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ioverridetheme/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

نمایانگر یک تم جایگزین‌کننده.
## متدها

| متد | توضیح |
| --- | --- |
| [isEmpty()](#isEmpty--) | مقدار True به این معنی است که ColorScheme، FontScheme، FormatScheme مقدار null دارند و هر گونه جایگزینی با این شیء تم غیرفعال است. |
| [initColorScheme()](#initColorScheme--) | با شیء جدید برای جایگزینی ColorScheme از InheritedTheme مقداردهی اولیه می‌کند. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | با شیء جدید برای جایگزینی ColorScheme از InheritedTheme مقداردهی اولیه می‌کند. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | با شیء جدید برای جایگزینی ColorScheme از InheritedTheme مقداردهی اولیه می‌کند. |
| [initFontScheme()](#initFontScheme--) | با شیء جدید برای جایگزینی FontScheme از InheritedTheme مقداردهی اولیه می‌کند. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | با شیء جدید برای جایگزینی FontScheme از InheritedTheme مقداردهی اولیه می‌کند. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | با شیء جدید برای جایگزینی FontScheme از InheritedTheme مقداردهی اولیه می‌کند. |
| [initFormatScheme()](#initFormatScheme--) | با شیء جدید برای جایگزینی FormatScheme از InheritedTheme مقداردهی اولیه می‌کند. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | با شیء جدید برای جایگزینی FormatScheme از InheritedTheme مقداردهی اولیه می‌کند. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | با شیء جدید برای جایگزینی FormatScheme از InheritedTheme مقداردهی اولیه می‌کند. |
| [clear()](#clear--) | ColorScheme، FontScheme، FormatScheme را به null تنظیم می‌کند تا هر گونه جایگزینی با این شیء تم غیرفعال شود. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

مقدار True به این معنی است که ColorScheme، FontScheme، FormatScheme مقدار null دارند و هر گونه جایگزینی با این شیء تم غیرفعال است. بولی فقط‌خواندنی.

**باز می‌گردد:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

با شیء جدید برای جایگزینی ColorScheme از InheritedTheme مقداردهی اولیه می‌کند.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

با شیء جدید برای جایگزینی ColorScheme از InheritedTheme مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | داده برای مقداردهی اولیه. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

با شیء جدید برای جایگزینی ColorScheme از InheritedTheme مقداردهی اولیه می‌کند و داده‌های این شیء جدید را با داده‌های ColorScheme از InheritedTheme مقداردهی می‌کند.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

با شیء جدید برای جایگزینی FontScheme از InheritedTheme مقداردهی اولیه می‌کند.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

با شیء جدید برای جایگزینی FontScheme از InheritedTheme مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | داده برای مقداردهی اولیه. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

با شیء جدید برای جایگزینی FontScheme از InheritedTheme مقداردهی اولیه می‌کند و داده‌های این شیء جدید را با داده‌های FontScheme از InheritedTheme مقداردهی می‌کند.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

با شیء جدید برای جایگزینی FormatScheme از InheritedTheme مقداردهی اولیه می‌کند.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

با شیء جدید برای جایگزینی FormatScheme از InheritedTheme مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | داده برای مقداردهی اولیه. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

با شیء جدید برای جایگزینی FormatScheme از InheritedTheme مقداردهی اولیه می‌کند و داده‌های این شیء جدید را با داده‌های FormatScheme از InheritedTheme مقداردهی می‌کند.

### clear() {#clear--}
```
public abstract void clear()
```

ColorScheme، FontScheme، FormatScheme را به null تنظیم می‌کند تا هر گونه جایگزینی با این شیء تم غیرفعال شود.