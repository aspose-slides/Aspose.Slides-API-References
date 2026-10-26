---
title: IOverrideTheme
second_title: Aspose.Slides for Java API Referansı
description: Geçersiz bir temayı temsil eder.
type: docs
url: /tr/com.aspose.slides/ioverridetheme/
---
**All Implemented Interfaces:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

Geçersiz bir temayı temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isEmpty()](#isEmpty--) | True değeri, ColorScheme, FontScheme, FormatScheme'in null olduğu ve bu tema nesnesiyle yapılan herhangi bir geçersiz kılmanın devre dışı bırakıldığı anlamına gelir. |
| [initColorScheme()](#initColorScheme--) | InheritedTheme'in ColorScheme'ini geçersiz kılmak için yeni bir nesneyle ColorScheme'i başlatır. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | InheritedTheme'in ColorScheme'ini geçersiz kılmak için yeni bir nesneyle ColorScheme'i başlatır. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | InheritedTheme'in ColorScheme'ini geçersiz kılmak için yeni bir nesneyle ColorScheme'i başlatır. |
| [initFontScheme()](#initFontScheme--) | InheritedTheme'in FontScheme'ini geçersiz kılmak için yeni bir nesneyle FontScheme'i başlatır. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | InheritedTheme'in FontScheme'ini geçersiz kılmak için yeni bir nesneyle FontScheme'i başlatır. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | InheritedTheme'in FontScheme'ini geçersiz kılmak için yeni bir nesneyle FontScheme'i başlatır. |
| [initFormatScheme()](#initFormatScheme--) | InheritedTheme'in FormatScheme'ini geçersiz kılmak için yeni bir nesneyle FormatScheme'i başlatır. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | InheritedTheme'in FormatScheme'ini geçersiz kılmak için yeni bir nesneyle FormatScheme'i başlatır. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | InheritedTheme'in FormatScheme'ini geçersiz kılmak için yeni bir nesneyle FormatScheme'i başlatır. |
| [clear()](#clear--) | ColorScheme, FontScheme, FormatScheme'i null olarak ayarlayarak bu tema nesnesiyle yapılan herhangi bir geçersiz kılmayı devre dışı bırakır. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

True değeri, ColorScheme, FontScheme, FormatScheme'in null olduğu ve bu tema nesnesiyle yapılan herhangi bir geçersiz kılmanın devre dışı bırakıldığı anlamına gelir. Salt okunur boolean.

**Döndürür:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

InheritedTheme'in ColorScheme'ini geçersiz kılmak için yeni bir nesneyle ColorScheme'i başlatır.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

InheritedTheme'in ColorScheme'ini geçersiz kılmak için yeni bir nesneyle ColorScheme'i başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Başlatılacak veri. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

InheritedTheme'in ColorScheme'ini geçersiz kılmak için yeni bir nesneyle ColorScheme'i başlatır ve bu yeni nesnenin verisini InheritedTheme'in ColorScheme'inin verisiyle başlatır.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

InheritedTheme'in FontScheme'ini geçersiz kılmak için yeni bir nesneyle FontScheme'i başlatır.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

InheritedTheme'in FontScheme'ini geçersiz kılmak için yeni bir nesneyle FontScheme'i başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Başlatılacak veri. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

InheritedTheme'in FontScheme'ini geçersiz kılmak için yeni bir nesneyle FontScheme'i başlatır ve bu yeni nesnenin verisini InheritedTheme'in FontScheme'inin verisiyle başlatır.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

InheritedTheme'in FormatScheme'ini geçersiz kılmak için yeni bir nesneyle FormatScheme'i başlatır.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

InheritedTheme'in FormatScheme'ini geçersiz kılmak için yeni bir nesneyle FormatScheme'i başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Başlatılacak veri. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

InheritedTheme'in FormatScheme'ini geçersiz kılmak için yeni bir nesneyle FormatScheme'i başlatır ve bu yeni nesnenin verisini InheritedTheme'in FormatScheme'inin verisiyle başlatır.

### clear() {#clear--}
```
public abstract void clear()
```

ColorScheme, FontScheme, FormatScheme'i null olarak ayarlayarak bu tema nesnesiyle yapılan herhangi bir geçersiz kılmayı devre dışı bırakır.