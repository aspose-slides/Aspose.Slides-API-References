---
title: IOverrideTheme
second_title: Aspose.Slides für Java API-Referenz
description: Stellt ein überschreibendes Theme dar.
type: docs
url: /de/com.aspose.slides/ioverridetheme/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

Stellt ein überschreibendes Theme dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isEmpty()](#isEmpty--) | Der boolesche Wert true bedeutet, dass ColorScheme, FontScheme, FormatScheme null sind und jedes Überschreiben mit diesem Theme-Objekt deaktiviert ist. |
| [initColorScheme()](#initColorScheme--) | Initialisiert ColorScheme mit einem neuen Objekt, um ColorScheme von InheritedTheme zu überschreiben. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Initialisiert ColorScheme mit einem neuen Objekt, um ColorScheme von InheritedTheme zu überschreiben. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Initialisiert ColorScheme mit einem neuen Objekt, um ColorScheme von InheritedTheme zu überschreiben. |
| [initFontScheme()](#initFontScheme--) | Initialisiert FontScheme mit einem neuen Objekt, um FontScheme von InheritedTheme zu überschreiben. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Initialisiert FontScheme mit einem neuen Objekt, um FontScheme von InheritedTheme zu überschreiben. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Initialisiert FontScheme mit einem neuen Objekt, um FontScheme von InheritedTheme zu überschreiben. |
| [initFormatScheme()](#initFormatScheme--) | Initialisiert FormatScheme mit einem neuen Objekt, um FormatScheme von InheritedTheme zu überschreiben. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Initialisiert FormatScheme mit einem neuen Objekt, um FormatScheme von InheritedTheme zu überschreiben. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Initialisiert FormatScheme mit einem neuen Objekt, um FormatScheme von InheritedTheme zu überschreiben. |
| [clear()](#clear--) | Setzt ColorScheme, FontScheme, FormatScheme auf null, um jedes Überschreiben mit diesem Theme-Objekt zu deaktivieren. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```


Der boolesche Wert true bedeutet, dass ColorScheme, FontScheme, FormatScheme null sind und jedes Überschreiben mit diesem Theme-Objekt deaktiviert ist. Schreibgeschützt boolean.

**Rückgabewert:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```


Initialisiert ColorScheme mit einem neuen Objekt, um ColorScheme von InheritedTheme zu überschreiben.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```


Initialisiert ColorScheme mit einem neuen Objekt, um ColorScheme von InheritedTheme zu überschreiben.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Daten, aus denen initialisiert wird. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```


Initialisiert ColorScheme mit einem neuen Objekt, um ColorScheme von InheritedTheme zu überschreiben, und füllt das neue Objekt mit den Daten des ColorScheme von InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```


Initialisiert FontScheme mit einem neuen Objekt, um FontScheme von InheritedTheme zu überschreiben.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```


Initialisiert FontScheme mit einem neuen Objekt, um FontScheme von InheritedTheme zu überschreiben.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Daten, aus denen initialisiert wird. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```


Initialisiert FontScheme mit einem neuen Objekt, um FontScheme von InheritedTheme zu überschreiben, und füllt das neue Objekt mit den Daten des FontScheme von InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```


Initialisiert FormatScheme mit einem neuen Objekt, um FormatScheme von InheritedTheme zu überschreiben.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```


Initialisiert FormatScheme mit einem neuen Objekt, um FormatScheme von InheritedTheme zu überschreiben.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Daten, aus denen initialisiert wird. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```


Initialisiert FormatScheme mit einem neuen Objekt, um FormatScheme von InheritedTheme zu überschreiben, und füllt das neue Objekt mit den Daten des FormatScheme von InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```


Setzt ColorScheme, FontScheme, FormatScheme auf null, um jedes Überschreiben mit diesem Theme-Objekt zu deaktivieren.