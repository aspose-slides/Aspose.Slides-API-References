---
title: IOverrideTheme
second_title: Aspose.Slides pro Java – referenční příručka API
description: Představuje přepisovatelný motiv.
type: docs
url: /cs/com.aspose.slides/ioverridetheme/
---
**All Implemented Interfaces:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

Představuje přepisovatelný motiv.
## Metody

| Metoda | Popis |
| --- | --- |
| [isEmpty()](#isEmpty--) | Hodnota true znamená, že ColorScheme, FontScheme, FormatScheme jsou null a jakékoli přepisování pomocí tohoto objektu motivu je zakázáno. |
| [initColorScheme()](#initColorScheme--) | Inicializuje ColorScheme novým objektem pro přepisování ColorScheme v InheritedTheme. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Inicializuje ColorScheme novým objektem pro přepisování ColorScheme v InheritedTheme. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Inicializuje ColorScheme novým objektem pro přepisování ColorScheme v InheritedTheme. |
| [initFontScheme()](#initFontScheme--) | Inicializuje FontScheme novým objektem pro přepisování FontScheme v InheritedTheme. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Inicializuje FontScheme novým objektem pro přepisování FontScheme v InheritedTheme. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Inicializuje FontScheme novým objektem pro přepisování FontScheme v InheritedTheme. |
| [initFormatScheme()](#initFormatScheme--) | Inicializuje FormatScheme novým objektem pro přepisování FormatScheme v InheritedTheme. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Inicializuje FormatScheme novým objektem pro přepisování FormatScheme v InheritedTheme. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Inicializuje FormatScheme novým objektem pro přepisování FormatScheme v InheritedTheme. |
| [clear()](#clear--) | Nastaví ColorScheme, FontScheme, FormatScheme na null, aby zakázal jakékoli přepisování pomocí tohoto objektu motivu. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```


Hodnota true znamená, že ColorScheme, FontScheme, FormatScheme jsou null a jakékoli přepisování pomocí tohoto objektu motivu je zakázáno. Pouze pro čtení boolean.

**Vrací:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```


Inicializuje ColorScheme novým objektem pro přepisování ColorScheme v InheritedTheme.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```


Inicializuje ColorScheme novým objektem pro přepisování ColorScheme v InheritedTheme.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Data pro inicializaci. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```


Inicializuje ColorScheme novým objektem pro přepisování ColorScheme v InheritedTheme. A inicializuje data tohoto nového objektu pomocí dat ColorScheme v InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```


Inicializuje FontScheme novým objektem pro přepisování FontScheme v InheritedTheme.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```


Inicializuje FontScheme novým objektem pro přepisování FontScheme v InheritedTheme.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Data pro inicializaci. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```


Inicializuje FontScheme novým objektem pro přepisování FontScheme v InheritedTheme. A inicializuje data tohoto nového objektu pomocí dat FontScheme v InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```


Inicializuje FormatScheme novým objektem pro přepisování FormatScheme v InheritedTheme.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```


Inicializuje FormatScheme novým objektem pro přepisování FormatScheme v InheritedTheme.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Data pro inicializaci. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```


Inicializuje FormatScheme novým objektem pro přepisování FormatScheme v InheritedTheme. A inicializuje data tohoto nového objektu pomocí dat FormatScheme v InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```


Nastaví ColorScheme, FontScheme, FormatScheme na null, aby zakázal jakékoli přepisování pomocí tohoto objektu motivu.