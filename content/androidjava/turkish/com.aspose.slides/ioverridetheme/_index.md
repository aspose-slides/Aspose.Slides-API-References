---
title: IOverrideTheme
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: Geçersiz kılan bir temayı temsil eder.
type: docs
url: /tr/com.aspose.slides/ioverridetheme/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

Geçersiz kılan bir temayı temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isEmpty()](#isEmpty--) | True değeri, ColorScheme, FontScheme ve FormatScheme'in null olduğu ve bu tema nesnesiyle herhangi bir geçersiz kılmanın devre dışı bırakıldığı anlamına gelir. |
| [initColorScheme()](#initColorScheme--) | InheritedTheme'in ColorScheme'ini geçersiz kılmak için yeni bir nesne ile ColorScheme'i başlatır. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | InheritedTheme'in ColorScheme'ini geçersiz kılmak için yeni bir nesne ile ColorScheme'i başlatır. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | InheritedTheme'in ColorScheme'ini geçersiz kılmak için yeni bir nesne ile ColorScheme'i başlatır. |
| [initFontScheme()](#initFontScheme--) | InheritedTheme'in FontScheme'ini geçersiz kılmak için yeni bir nesne ile FontScheme'i başlatır. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | InheritedTheme'in FontScheme'ini geçersiz kılmak için yeni bir nesne ile FontScheme'i başlatır. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | InheritedTheme'in FontScheme'ini geçersiz kılmak için yeni bir nesne ile FontScheme'i başlatır. |
| [initFormatScheme()](#initFormatScheme--) | InheritedTheme'in FormatScheme'ini geçersiz kılmak için yeni bir nesne ile FormatScheme'i başlatır. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | InheritedTheme'in FormatScheme'ini geçersiz kılmak için yeni bir nesne ile FormatScheme'i başlatır. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | InheritedTheme'in FormatScheme'ini geçersiz kılmak için yeni bir nesne ile FormatScheme'i başlatır. |
| [clear()](#clear--) | ColorScheme, FontScheme ve FormatScheme'i null olarak ayarlayarak bu tema nesnesiyle herhangi bir geçersiz kılmayı devre dışı bırakır. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

True değeri, ColorScheme, FontScheme ve FormatScheme'in null olduğu ve bu tema nesnesiyle herhangi bir geçersiz kılmanın devre dışı bırakıldığı anlamına gelir. Yalnızca okuma boole.

**Döndürür:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

InheritedTheme'in ColorScheme'ini geçersiz kılmak için yeni bir nesne ile ColorScheme'i başlatır.
### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

InheritedTheme'in ColorScheme'ini geçersiz kılmak için yeni bir nesne ile ColorScheme'i başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Başlatma verisi. |
### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

InheritedTheme'in ColorScheme'ini geçersiz kılmak için yeni bir nesne ile ColorScheme'i başlatır ve bu yeni nesnenin verilerini InheritedTheme'in ColorScheme'inden alır.
### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

InheritedTheme'in FontScheme'ini geçersiz kılmak için yeni bir nesne ile FontScheme'i başlatır.
### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

InheritedTheme'in FontScheme'ini geçersiz kılmak için yeni bir nesne ile FontScheme'i başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Başlatma verisi. |
### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

InheritedTheme'in FontScheme'ini geçersiz kılmak için yeni bir nesne ile FontScheme'i başlatır ve bu yeni nesnenin verilerini InheritedTheme'in FontScheme'inden alır.
### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

InheritedTheme'in FormatScheme'ini geçersiz kılmak için yeni bir nesne ile FormatScheme'i başlatır.
### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

InheritedTheme'in FormatScheme'ini geçersiz kılmak için yeni bir nesne ile FormatScheme'i başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Başlatma verisi. |
### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

InheritedTheme'in FormatScheme'ini geçersiz kılmak için yeni bir nesne ile FormatScheme'i başlatır ve bu yeni nesnenin verilerini InheritedTheme'in FormatScheme'inden alır.
### clear() {#clear--}
```
public abstract void clear()
```

ColorScheme, FontScheme ve FormatScheme'i null olarak ayarlayarak bu tema nesnesiyle herhangi bir geçersiz kılmayı devre dışı bırakır.