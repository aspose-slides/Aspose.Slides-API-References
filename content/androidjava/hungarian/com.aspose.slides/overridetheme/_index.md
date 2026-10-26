---
title: OverrideTheme
second_title: Aspose.Slides for Android a Java API-n keresztül
description: Egy felülíró témát képvisel.
type: docs
url: /hu/com.aspose.slides/overridetheme/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**Minden megvalósított interfész:**
[com.aspose.slides.IOverrideTheme](../../com.aspose.slides/ioverridetheme)
```
public final class OverrideTheme extends Theme implements IOverrideTheme
```

Egy felülíró témát képvisel.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [initColorScheme()](#initColorScheme--) | Inicializálja a ColorScheme-et egy új objektummal az InheritedTheme ColorScheme felülbírálásához. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Inicializálja a ColorScheme-et egy új objektummal az InheritedTheme ColorScheme felülbírálásához. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Inicializálja a ColorScheme-et egy új objektummal az InheritedTheme ColorScheme felülbírálásához. |
| [initFontScheme()](#initFontScheme--) | Inicializálja a FontScheme-et egy új objektummal az InheritedTheme FontScheme felülbírálásához. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Inicializálja a FontScheme-et egy új objektummal az InheritedTheme FontScheme felülbírálásához. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Inicializálja a FontScheme-et egy új objektummal az InheritedTheme FontScheme felülbírálásához. |
| [initFormatScheme()](#initFormatScheme--) | Inicializálja a FormatScheme-et egy új objektummal az InheritedTheme FormatScheme felülbírálásához. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Inicializálja a FormatScheme-et egy új objektummal az InheritedTheme FormatScheme felülbírálásához. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Inicializálja a FormatScheme-et egy új objektummal az InheritedTheme FormatScheme felülbírálásához. |
| [getColorScheme()](#getColorScheme--) | Visszaadja a ColorScheme-et. |
| [getFontScheme()](#getFontScheme--) | Visszaadja a FontScheme-et. |
| [getFormatScheme()](#getFormatScheme--) | Visszaadja a shape format scheme-et. |
| [isEmpty()](#isEmpty--) | Az igaz érték azt jelenti, hogy a ColorScheme, a FontScheme és a FormatScheme null, és a témaobjektummal történő bármilyen felülbírálás le van tiltva. |
| [clear()](#clear--) | A ColorScheme-et, a FontScheme-et és a FormatScheme-et null értékre állítja, hogy letiltsa a témával történő felülbírálást. |
| [getVersion()](#getVersion--) |  |
### initColorScheme() {#initColorScheme--}
```
public final void initColorScheme()
```

Inicializálja a ColorScheme-et egy új objektummal az InheritedTheme ColorScheme felülbírálásához.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public final void initColorSchemeFrom(IColorScheme colorScheme)
```

Inicializálja a ColorScheme-et egy új objektummal az InheritedTheme ColorScheme felülbírálásához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Az inicializáláshoz használandó adatok. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public final void initColorSchemeFromInherited()
```

Inicializálja a ColorScheme-et egy új objektummal az InheritedTheme ColorScheme felülbírálásához, és a new objektum adatait az InheritedTheme ColorScheme adataival tölti fel.

### initFontScheme() {#initFontScheme--}
```
public final void initFontScheme()
```

Inicializálja a FontScheme-et egy új objektummal az InheritedTheme FontScheme felülbírálásához.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public final void initFontSchemeFrom(IFontScheme fontScheme)
```

Inicializálja a FontScheme-et egy új objektummal az InheritedTheme FontScheme felülbírálásához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Az inicializáláshoz használandó adatok. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public final void initFontSchemeFromInherited()
```

Inicializálja a FontScheme-et egy új objektummal az InheritedTheme FontScheme felülbírálásához, és a new objektum adatait az InheritedTheme FontScheme adataival tölti fel.

### initFormatScheme() {#initFormatScheme--}
```
public final void initFormatScheme()
```

Inicializálja a FormatScheme-et egy új objektummal az InheritedTheme FormatScheme felülbírálásához.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public final void initFormatSchemeFrom(IFormatScheme formatScheme)
```

Inicializálja a FormatScheme-et egy új objektummal az InheritedTheme FormatScheme felülbírálásához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Az inicializáláshoz használandó adatok. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public final void initFormatSchemeFromInherited()
```

Inicializálja a FormatScheme-et egy új objektummal az InheritedTheme FormatScheme felülbírálásához, és a new objektum adatait az InheritedTheme FormatScheme adataival tölti fel.

### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```

Visszaadja a ColorScheme-et. Csak olvasható [IColorScheme](../../com.aspose.slides/icolorscheme).

**Visszatérési érték:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```

Visszaadja a FontScheme-et. Csak olvasható [IFontScheme](../../com.aspose.slides/ifontscheme).

**Visszatérési érték:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```

Visszaadja a shape format scheme-et. Csak olvasható [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Visszatérési érték:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```

Az igaz érték azt jelenti, hogy a ColorScheme, a FontScheme és a FormatScheme null, és a témaobjektummal történő bármilyen felülbírálás le van tiltva. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### clear() {#clear--}
```
public final void clear()
```

A ColorScheme-et, a FontScheme-et és a FormatScheme-et null értékre állítja, hogy letiltsa a témával történő felülbírálást.

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatérési érték:**
long