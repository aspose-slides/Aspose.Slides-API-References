---
title: IOverrideTheme
second_title: Aspose.Slides voor Java API Referentie
description: Stelt een overschrijfend thema voor.
type: docs
url: /nl/com.aspose.slides/ioverridetheme/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

Stelt een overschrijfend thema voor.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isEmpty()](#isEmpty--) | De True-waarde betekent dat ColorScheme, FontScheme, FormatScheme null is en elke overschrijving met dit thema-object wordt uitgeschakeld. |
| [initColorScheme()](#initColorScheme--) | Initialiseer ColorScheme met een nieuw object om ColorScheme van InheritedTheme te overschrijven. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Initialiseer ColorScheme met een nieuw object om ColorScheme van InheritedTheme te overschrijven. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Initialiseer ColorScheme met een nieuw object om ColorScheme van InheritedTheme te overschrijven. |
| [initFontScheme()](#initFontScheme--) | Initialiseer FontScheme met een nieuw object om FontScheme van InheritedTheme te overschrijven. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Initialiseer FontScheme met een nieuw object om FontScheme van InheritedTheme te overschrijven. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Initialiseer FontScheme met een nieuw object om FontScheme van InheritedTheme te overschrijven. |
| [initFormatScheme()](#initFormatScheme--) | Initialiseer FormatScheme met een nieuw object om FormatScheme van InheritedTheme te overschrijven. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Initialiseer FormatScheme met een nieuw object om FormatScheme van InheritedTheme te overschrijven. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Initialiseer FormatScheme met een nieuw object om FormatScheme van InheritedTheme te overschrijven. |
| [clear()](#clear--) | Stel ColorScheme, FontScheme, FormatScheme in op null om elke overschrijving met dit thema-object uit te schakelen. |

### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

De True-waarde betekent dat ColorScheme, FontScheme, FormatScheme null is en elke overschrijving met dit thema-object wordt uitgeschakeld. Alleen-lezen boolean.

**Retour:**
boolean

### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

Initialiseer ColorScheme met een nieuw object om ColorScheme van InheritedTheme te overschrijven.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

Initialiseer ColorScheme met een nieuw object om ColorScheme van InheritedTheme te overschrijven.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Gegevens om van te initialiseren. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

Initialiseer ColorScheme met een nieuw object om ColorScheme van InheritedTheme te overschrijven. En initialiseer de gegevens van dit nieuwe object met de gegevens van de ColorScheme van InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

Initialiseer FontScheme met een nieuw object om FontScheme van InheritedTheme te overschrijven.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

Initialiseer FontScheme met een nieuw object om FontScheme van InheritedTheme te overschrijven.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Gegevens om van te initialiseren. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

Initialiseer FontScheme met een nieuw object om FontScheme van InheritedTheme te overschrijven. En initialiseer de gegevens van dit nieuwe object met de gegevens van de FontScheme van InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

Initialiseer FormatScheme met een nieuw object om FormatScheme van InheritedTheme te overschrijven.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

Initialiseer FormatScheme met een nieuw object om FormatScheme van InheritedTheme te overschrijven.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Gegevens om van te initialiseren. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

Initialiseer FormatScheme met een nieuw object om FormatScheme van InheritedTheme te overschrijven. En initialiseer de gegevens van dit nieuwe object met de gegevens van de FormatScheme van InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```

Stel ColorScheme, FontScheme, FormatScheme in op null om elke overschrijving met dit thema-object uit te schakelen.