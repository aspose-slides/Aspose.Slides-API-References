---
title: IOverrideTheme
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [isEmpty()](#isEmpty--) | Ein true-Wert bedeutet, dass ColorScheme, FontScheme, FormatScheme null ist und jede Überschreibung mit diesem Theme-Objekt deaktiviert ist. |
| [initColorScheme()](#initColorScheme--) | Initialisiert ColorScheme mit einem neuen Objekt zur Überschreibung des ColorScheme von InheritedTheme. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Initialisiert ColorScheme mit einem neuen Objekt zur Überschreibung des ColorScheme von InheritedTheme. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Initialisiert ColorScheme mit einem neuen Objekt zur Überschreibung des ColorScheme von InheritedTheme. |
| [initFontScheme()](#initFontScheme--) | Initialisiert FontScheme mit einem neuen Objekt zur Überschreibung des FontScheme von InheritedTheme. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Initialisiert FontScheme mit einem neuen Objekt zur Überschreibung des FontScheme von InheritedTheme. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Initialisiert FontScheme mit einem neuen Objekt zur Überschreibung des FontScheme von InheritedTheme. |
| [initFormatScheme()](#initFormatScheme--) | Initialisiert FormatScheme mit einem neuen Objekt zur Überschreibung des FormatScheme von InheritedTheme. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Initialisiert FormatScheme mit einem neuen Objekt zur Überschreibung des FormatScheme von InheritedTheme. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Initialisiert FormatScheme mit einem neuen Objekt zur Überschreibung des FormatScheme von InheritedTheme. |
| [clear()](#clear--) | Setzt ColorScheme, FontScheme, FormatScheme auf null, um jede Überschreibung mit diesem Theme-Objekt zu deaktivieren. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```


Ein true-Wert bedeutet, dass ColorScheme, FontScheme, FormatScheme null ist und jede Überschreibung mit diesem Theme-Objekt deaktiviert ist. Nur-Lese-Boolean.

**Rückgabewert:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```


Initialisiert ColorScheme mit einem neuen Objekt zur Überschreibung des ColorScheme von InheritedTheme.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```


Initialisiert ColorScheme mit einem neuen Objekt zur Überschreibung des ColorScheme von InheritedTheme.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Daten, aus denen initialisiert werden soll. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```


Initialisiert ColorScheme mit einem neuen Objekt zur Überschreibung des ColorScheme von InheritedTheme und initialisiert die Daten dieses neuen Objekts mit den Daten des ColorScheme von InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```


Initialisiert FontScheme mit einem neuen Objekt zur Überschreibung des FontScheme von InheritedTheme.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```


Initialisiert FontScheme mit einem neuen Objekt zur Überschreibung des FontScheme von InheritedTheme.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Daten, aus denen initialisiert werden soll. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```


Initialisiert FontScheme mit einem neuen Objekt zur Überschreibung des FontScheme von InheritedTheme und initialisiert die Daten dieses neuen Objekts mit den Daten des FontScheme von InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```


Initialisiert FormatScheme mit einem neuen Objekt zur Überschreibung des FormatScheme von InheritedTheme.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```


Initialisiert FormatScheme mit einem neuen Objekt zur Überschreibung des FormatScheme von InheritedTheme.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Daten, aus denen initialisiert werden soll. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```


Initialisiert FormatScheme mit einem neuen Objekt zur Überschreibung des FormatScheme von InheritedTheme und initialisiert die Daten dieses neuen Objekts mit den Daten des FormatScheme von InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```


Setzt ColorScheme, FontScheme, FormatScheme auf null, um jede Überschreibung mit diesem Theme-Objekt zu deaktivieren.