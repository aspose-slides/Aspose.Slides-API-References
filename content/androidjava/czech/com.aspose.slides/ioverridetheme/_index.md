---
title: IOverrideTheme
second_title: Aspose.Slides pro Android pomocí reference Java API
description: Reprezentuje přepisující téma.
type: docs
url: /cs/com.aspose.slides/ioverridetheme/
---
**All Implemented Interfaces:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

Reprezentuje přepisující téma.
## Metody

| Metoda | Popis |
| --- | --- |
| [isEmpty()](#isEmpty--) | Hodnota true znamená, že ColorScheme, FontScheme, FormatScheme jsou null a jakékoli přepisování pomocí tohoto objektu tématu je zakázáno. |
| [initColorScheme()](#initColorScheme--) | Inicializuje ColorScheme novým objektem pro přepsání ColorScheme zděděného tématu. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Inicializuje ColorScheme novým objektem pro přepsání ColorScheme zděděného tématu. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Inicializuje ColorScheme novým objektem pro přepsání ColorScheme zděděného tématu. |
| [initFontScheme()](#initFontScheme--) | Inicializuje FontScheme novým objektem pro přepsání FontScheme zděděného tématu. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Inicializuje FontScheme novým objektem pro přepsání FontScheme zděděného tématu. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Inicializuje FontScheme novým objektem pro přepsání FontScheme zděděného tématu. |
| [initFormatScheme()](#initFormatScheme--) | Inicializuje FormatScheme novým objektem pro přepsání FormatScheme zděděného tématu. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Inicializuje FormatScheme novým objektem pro přepsání FormatScheme zděděného tématu. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Inicializuje FormatScheme novým objektem pro přepsání FormatScheme zděděného tématu. |
| [clear()](#clear--) | Nastaví ColorScheme, FontScheme, FormatScheme na null, aby se zakázalo jakékoli přepisování pomocí tohoto objektu tématu. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

Hodnota true znamená, že ColorScheme, FontScheme, FormatScheme jsou null a jakékoli přepisování pomocí tohoto objektu tématu je zakázáno. Pouze pro čtení boolean.

**Vrací:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

Inicializuje ColorScheme novým objektem pro přepsání ColorScheme zděděného tématu.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

Inicializuje ColorScheme novým objektem pro přepsání ColorScheme zděděného tématu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Data pro inicializaci. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

Inicializuje ColorScheme novým objektem pro přepsání ColorScheme zděděného tématu. A také inicializuje data tohoto nového objektu daty ColorScheme zděděného tématu.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

Inicializuje FontScheme novým objektem pro přepsání FontScheme zděděného tématu.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

Inicializuje FontScheme novým objektem pro přepsání FontScheme zděděného tématu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Data pro inicializaci. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

Inicializuje FontScheme novým objektem pro přepsání FontScheme zděděného tématu. A také inicializuje data tohoto nového objektu daty FontScheme zděděného tématu.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

Inicializuje FormatScheme novým objektem pro přepsání FormatScheme zděděného tématu.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

Inicializuje FormatScheme novým objektem pro přepsání FormatScheme zděděného tématu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Data pro inicializaci. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

Inicializuje FormatScheme novým objektem pro přepsání FormatScheme zděděného tématu. A také inicializuje data tohoto nového objektu daty FormatScheme zděděného tématu.

### clear() {#clear--}
```
public abstract void clear()
```

Nastaví ColorScheme, FontScheme, FormatScheme na null, aby se zakázalo jakékoli přepisování pomocí tohoto objektu tématu.