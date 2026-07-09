---
title: IOverrideTheme
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente un thème de substitution.
type: docs
url: /fr/com.aspose.slides/ioverridetheme/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

Représente un thème de substitution.

## Méthodes

| Méthode | Description |
| --- | --- |
| [isEmpty()](#isEmpty--) | Une valeur vraie signifie que ColorScheme, FontScheme, FormatScheme sont null et que toute substitution avec cet objet thème est désactivée. |
| [initColorScheme()](#initColorScheme--) | Initialise ColorScheme avec un nouvel objet pour remplacer ColorScheme de InheritedTheme. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Initialise ColorScheme avec un nouvel objet pour remplacer ColorScheme de InheritedTheme. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Initialise ColorScheme avec un nouvel objet pour remplacer ColorScheme de InheritedTheme. |
| [initFontScheme()](#initFontScheme--) | Initialise FontScheme avec un nouvel objet pour remplacer FontScheme de InheritedTheme. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Initialise FontScheme avec un nouvel objet pour remplacer FontScheme de InheritedTheme. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Initialise FontScheme avec un nouvel objet pour remplacer FontScheme de InheritedTheme. |
| [initFormatScheme()](#initFormatScheme--) | Initialise FormatScheme avec un nouvel objet pour remplacer FormatScheme de InheritedTheme. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Initialise FormatScheme avec un nouvel objet pour remplacer FormatScheme de InheritedTheme. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Initialise FormatScheme avec un nouvel objet pour remplacer FormatScheme de InheritedTheme. |
| [clear()](#clear--) | Définit ColorScheme, FontScheme, FormatScheme à null pour désactiver toute substitution avec cet objet thème. |

### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

Une valeur vraie signifie que ColorScheme, FontScheme, FormatScheme sont null et que toute substitution avec cet objet thème est désactivée. booléen en lecture seule.

**Renvoie :**
boolean

### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

Initialise ColorScheme avec un nouvel objet pour remplacer ColorScheme de InheritedTheme.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

Initialise ColorScheme avec un nouvel objet pour remplacer ColorScheme de InheritedTheme.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Données à initialiser. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

Initialise ColorScheme avec un nouvel objet pour remplacer ColorScheme de InheritedTheme et initialise les données de ce nouvel objet avec les données du ColorScheme de InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

Initialise FontScheme avec un nouvel objet pour remplacer FontScheme de InheritedTheme.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

Initialise FontScheme avec un nouvel objet pour remplacer FontScheme de InheritedTheme.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Données à initialiser. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

Initialise FontScheme avec un nouvel objet pour remplacer FontScheme de InheritedTheme et initialise les données de ce nouvel objet avec les données du FontScheme de InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

Initialise FormatScheme avec un nouvel objet pour remplacer FormatScheme de InheritedTheme.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

Initialise FormatScheme avec un nouvel objet pour remplacer FormatScheme de InheritedTheme.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Données à initialiser. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

Initialise FormatScheme avec un nouvel objet pour remplacer FormatScheme de InheritedTheme et initialise les données de ce nouvel objet avec les données du FormatScheme de InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```

Définit ColorScheme, FontScheme, FormatScheme à null pour désactiver toute substitution avec cet objet thème.