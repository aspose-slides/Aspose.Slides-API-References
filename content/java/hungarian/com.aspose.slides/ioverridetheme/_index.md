---
title: IOverrideTheme
second_title: Aspose.Slides Java API hivatkozás
description: Egy felülbíráló témát képvisel.
type: docs
url: /hu/com.aspose.slides/ioverridetheme/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

Egy felülbíráló témát képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [isEmpty()](#isEmpty--) | Az igaz érték azt jelenti, hogy a ColorScheme, FontScheme, FormatScheme null, és a témás objektummal történő felülbírálás le van tiltva. |
| [initColorScheme()](#initColorScheme--) | A ColorScheme inicializálása új objektummal az InheritedTheme ColorScheme felülbírálásához. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | A ColorScheme inicializálása új objektummal az InheritedTheme ColorScheme felülbírálásához. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | A ColorScheme inicializálása új objektummal az InheritedTheme ColorScheme felülbírálásához. |
| [initFontScheme()](#initFontScheme--) | A FontScheme inicializálása új objektummal az InheritedTheme FontScheme felülbírálásához. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | A FontScheme inicializálása új objektummal az InheritedTheme FontScheme felülbírálásához. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | A FontScheme inicializálása új objektummal az InheritedTheme FontScheme felülbírálásához. |
| [initFormatScheme()](#initFormatScheme--) | A FormatScheme inicializálása új objektummal az InheritedTheme FormatScheme felülbírálásához. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | A FormatScheme inicializálása új objektummal az InheritedTheme FormatScheme felülbírálásához. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | A FormatScheme inicializálása új objektummal az InheritedTheme FormatScheme felülbírálásához. |
| [clear()](#clear--) | A ColorScheme, FontScheme, FormatScheme null értékre állítása a témás objektummal történő felülbírálás letiltásához. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

Az igaz érték azt jelenti, hogy a ColorScheme, FontScheme, FormatScheme null, és a témás objektummal történő felülbírálás le van tiltva. Csak olvasható boolean.

**Visszatér:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

A ColorScheme inicializálása új objektummal az InheritedTheme ColorScheme felülbírálásához.
### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

A ColorScheme inicializálása új objektummal az InheritedTheme ColorScheme felülbírálásához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Az inicializáláshoz használt adat. |
### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

A ColorScheme inicializálása új objektummal az InheritedTheme ColorScheme felülbírálásához. És az új objektum adatait az InheritedTheme ColorScheme adataival inicializálja.
### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

A FontScheme inicializálása új objektummal az InheritedTheme FontScheme felülbírálásához.
### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

A FontScheme inicializálása új objektummal az InheritedTheme FontScheme felülbírálásához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Az inicializáláshoz használt adat. |
### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

A FontScheme inicializálása új objektummal az InheritedTheme FontScheme felülbírálásához. És az új objektum adatait az InheritedTheme FontScheme adataival inicializálja.
### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

A FormatScheme inicializálása új objektummal az InheritedTheme FormatScheme felülbírálásához.
### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

A FormatScheme inicializálása új objektummal az InheritedTheme FormatScheme felülbírálásához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Az inicializáláshoz használt adat. |
### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

A FormatScheme inicializálása új objektummal az InheritedTheme FormatScheme felülbírálásához. És az új objektum adatait az InheritedTheme FormatScheme adataival inicializálja.
### clear() {#clear--}
```
public abstract void clear()
```

A ColorScheme, FontScheme, FormatScheme null értékre állítása a témás objektummal történő felülbírálás letiltásához.