---
title: IOverrideTheme
second_title: Aspose.Slides Androidra a Java API-referencia
description: Egy felülíró témát képvisel.
type: docs
url: /hu/com.aspose.slides/ioverridetheme/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

Egy felülíró témát képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [isEmpty()](#isEmpty--) | Az igaz érték azt jelenti, hogy a ColorScheme, a FontScheme és a FormatScheme null, és a témát objektummal való felülírás le van tiltva. |
| [initColorScheme()](#initColorScheme--) | A ColorScheme-t új objektummal inicializálja az InheritedTheme ColorScheme felülírásához. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | A ColorScheme-t új objektummal inicializálja az InheritedTheme ColorScheme felülírásához. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | A ColorScheme-t új objektummal inicializálja az InheritedTheme ColorScheme felülírásához. |
| [initFontScheme()](#initFontScheme--) | A FontScheme-t új objektummal inicializálja az InheritedTheme FontScheme felülírásához. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | A FontScheme-t új objektummal inicializálja az InheritedTheme FontScheme felülírásához. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | A FontScheme-t új objektummal inicializálja az InheritedTheme FontScheme felülírásához. |
| [initFormatScheme()](#initFormatScheme--) | A FormatScheme-t új objektummal inicializálja az InheritedTheme FormatScheme felülírásához. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | A FormatScheme-t új objektummal inicializálja az InheritedTheme FormatScheme felülírásához. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | A FormatScheme-t új objektummal inicializálja az InheritedTheme FormatScheme felülírásához. |
| [clear()](#clear--) | A ColorScheme, a FontScheme és a FormatScheme null beállítása letiltja a témát objektummal való felülírást. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

Az igaz érték azt jelenti, hogy a ColorScheme, a FontScheme és a FormatScheme null, és a témát objektummal való felülírás le van tiltva. Írásvédett logikai érték.

**Visszatér:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

A ColorScheme-t új objektummal inicializálja az InheritedTheme ColorScheme felülírásához.
### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

A ColorScheme-t új objektummal inicializálja az InheritedTheme ColorScheme felülírásához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | A kiindulási adatok. |
### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

A ColorScheme-t új objektummal inicializálja az InheritedTheme ColorScheme felülírásához. És a új objektum adatait az InheritedTheme ColorScheme adataival inicializálja.
### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

A FontScheme-t új objektummal inicializálja az InheritedTheme FontScheme felülírásához.
### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

A FontScheme-t új objektummal inicializálja az InheritedTheme FontScheme felülírásához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | A kiindulási adatok. |
### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

A FontScheme-t új objektummal inicializálja az InheritedTheme FontScheme felülírásához. És a új objektum adatait az InheritedTheme FontScheme adataival inicializálja.
### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

A FormatScheme-t új objektummal inicializálja az InheritedTheme FormatScheme felülírásához.
### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

A FormatScheme-t új objektummal inicializálja az InheritedTheme FormatScheme felülírásához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | A kiindulási adatok. |
### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

A FormatScheme-t új objektummal inicializálja az InheritedTheme FormatScheme felülírásához. És a új objektum adatait az InheritedTheme FormatScheme adataival inicializálja.
### clear() {#clear--}
```
public abstract void clear()
```

A ColorScheme, a FontScheme és a FormatScheme null beállítása letiltja a témát objektummal való felülírást.