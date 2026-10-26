---
title: MasterTheme
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Představuje hlavní motiv.
type: docs
url: /cs/com.aspose.slides/mastertheme/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**Všechny implementované rozhraní:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

Představuje hlavní motiv.
## Metody

| Metoda | Popis |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Vrací barevné schéma. |
| [getFontScheme()](#getFontScheme--) | Vrací schéma písem. |
| [getFormatScheme()](#getFormatScheme--) | Vrací schéma formátování tvarů. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Vrací kolekci dalších barevných schémat. |
| [getName()](#getName--) | Vrací název motivu. |
| [setName(String value)](#setName-java.lang.String-) | Vrací název motivu. |
| [getVersion()](#getVersion--) |  |

### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```

Vrací barevné schéma. Pouze pro čtení [IColorScheme](../../com.aspose.slides/icolorscheme).

**Vrátí:**
[IColorScheme](../../com.aspose.slides/icolorscheme)

### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```

Vrací schéma písem. Pouze pro čtení [IFontScheme](../../com.aspose.slides/ifontscheme).

**Vrátí:**
[IFontScheme](../../com.aspose.slides/ifontscheme)

### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

Vrací schéma formátování tvarů. Pouze pro čtení [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Vrátí:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)

### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```

Vrací kolekci dalších barevných schémat. Tato schémata neovlivňují vzhled prezentace, lze je vybrat jako hlavní barevné schéma pro snímek. Pouze pro čtení [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Vrátí:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)

### getName() {#getName--}
```
public final String getName()
```

Vrací název motivu. Čtení/Zápis String.

**Vrátí:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Vrací název motivu. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze pro čtení long.

**Vrátí:**
long