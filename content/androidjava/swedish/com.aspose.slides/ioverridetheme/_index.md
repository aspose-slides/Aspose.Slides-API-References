---
title: IOverrideTheme
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett överskrivande tema.
type: docs
url: /sv/com.aspose.slides/ioverridetheme/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

Representerar ett överskrivande tema.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isEmpty()](#isEmpty--) | Sant värde betyder att ColorScheme, FontScheme, FormatScheme är null och alla överskrivningar med detta temaattribut är inaktiverade. |
| [initColorScheme()](#initColorScheme--) | Initiera ColorScheme med ett nytt objekt för att åsidosätta ColorScheme av InheritedTheme. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Initiera ColorScheme med ett nytt objekt för att åsidosätta ColorScheme av InheritedTheme. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Initiera ColorScheme med ett nytt objekt för att åsidosätta ColorScheme av InheritedTheme. |
| [initFontScheme()](#initFontScheme--) | Initiera FontScheme med ett nytt objekt för att åsidosätta FontScheme av InheritedTheme. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Initiera FontScheme med ett nytt objekt för att åsidosätta FontScheme av InheritedTheme. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Initiera FontScheme med ett nytt objekt för att åsidosätta FontScheme av InheritedTheme. |
| [initFormatScheme()](#initFormatScheme--) | Initiera FormatScheme med ett nytt objekt för att åsidosätta FormatScheme av InheritedTheme. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Initiera FormatScheme med ett nytt objekt för att åsidosätta FormatScheme av InheritedTheme. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Initiera FormatScheme med ett nytt objekt för att åsidosätta FormatScheme av InheritedTheme. |
| [clear()](#clear--) | Ställ in ColorScheme, FontScheme, FormatScheme till null för att inaktivera alla överskrivningar med detta temaattribut. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

Sant värde betyder att ColorScheme, FontScheme, FormatScheme är null och alla överskrivningar med detta temaattribut är inaktiverade. Skrivskyddad boolean.

**Returnerar:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

Initiera ColorScheme med ett nytt objekt för att åsidosätta ColorScheme av InheritedTheme.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

Initiera ColorScheme med ett nytt objekt för att åsidosätta ColorScheme av InheritedTheme.

Parametrar:
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Data att initiera från. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

Initiera ColorScheme med ett nytt objekt för att åsidosätta ColorScheme av InheritedTheme. Och initiera data för detta nya objekt med data från ColorScheme av InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

Initiera FontScheme med ett nytt objekt för att åsidosätta FontScheme av InheritedTheme.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

Initiera FontScheme med ett nytt objekt för att åsidosätta FontScheme av InheritedTheme.

Parametrar:
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Data att initiera från. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

Initiera FontScheme med ett nytt objekt för att åsidosätta FontScheme av InheritedTheme. Och initiera data för detta nya objekt med data från FontScheme av InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

Initiera FormatScheme med ett nytt objekt för att åsidosätta FormatScheme av InheritedTheme.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

Initiera FormatScheme med ett nytt objekt för att åsidosätta FormatScheme av InheritedTheme.

Parametrar:
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Data att initiera från. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

Initiera FormatScheme med ett nytt objekt för att åsidosätta FormatScheme av InheritedTheme. Och initiera data för detta nya objekt med data från FormatScheme av InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```

Ställ in ColorScheme, FontScheme, FormatScheme till null för att inaktivera alla överskrivningar med detta temaattribut.