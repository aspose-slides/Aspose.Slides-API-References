---
title: IOverrideTheme
second_title: Référence de l'API Aspose.Slides pour Java
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
| [isEmpty()](#isEmpty--) | Une valeur vraie indique que ColorScheme, FontScheme, FormatScheme sont null et que toute substitution avec cet objet thème est désactivée. |
| [initColorScheme()](#initColorScheme--) | Une valeur vraie indique que ColorScheme, FontScheme, FormatScheme sont null et que toute substitution avec cet objet thème est désactivée. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Une valeur vraie indique que ColorScheme, FontScheme, FormatScheme sont null et que toute substitution avec cet objet thème est désactivée. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Une valeur vraie indique que ColorScheme, FontScheme, FormatScheme sont null et que toute substitution avec cet objet thème est désactivée. |
| [initFontScheme()](#initFontScheme--) | Une valeur vraie indique que ColorScheme, FontScheme, FormatScheme sont null et que toute substitution avec cet objet thème est désactivée. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Une valeur vraie indique que ColorScheme, FontScheme, FormatScheme sont null et que toute substitution avec cet objet thème est désactivée. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Une valeur vraie indique que ColorScheme, FontScheme, FormatScheme sont null et que toute substitution avec cet objet thème est désactivée. |
| [initFormatScheme()](#initFormatScheme--) | Une valeur vraie indique que ColorScheme, FontScheme, FormatScheme sont null et que toute substitution avec cet objet thème est désactivée. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Une valeur vraie indique que ColorScheme, FontScheme, FormatScheme sont null et que toute substitution avec cet objet thème est désactivée. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Une valeur vraie indique que ColorScheme, FontScheme, FormatScheme sont null et que toute substitution avec cet objet thème est désactivée. |
| [clear()](#clear--) | Définir ColorScheme, FontScheme, FormatScheme sur null pour désactiver toute substitution avec cet objet thème. |

### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

Une valeur vraie indique que ColorScheme, FontScheme, FormatScheme sont null et que toute substitution avec cet objet thème est désactivée. Booléen en lecture seule.

**Retourne :**  
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

Initialise ColorScheme avec un nouvel objet pour remplacer ColorScheme de InheritedTheme. Et initialise les données de ce nouvel objet avec celles du ColorScheme de InheritedTheme.

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

Initialise FontScheme avec un nouvel objet pour remplacer FontScheme de InheritedTheme. Et initialise les données de ce nouvel objet avec celles du FontScheme de InheritedTheme.

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

Initialise FormatScheme avec un nouvel objet pour remplacer FormatScheme de InheritedTheme. Et initialise les données de ce nouvel objet avec celles du FormatScheme de InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```

Définir ColorScheme, FontScheme, FormatScheme sur null pour désactiver toute substitution avec cet objet thème.