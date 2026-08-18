---
title: BaseOverrideThemeManager
second_title: Aspose.Slides for Java API-referencia
description: Alap osztály azoknak az osztályoknak, amelyek hozzáférést biztosítanak különböző típusú felülírt témákhoz.
type: docs
url: /hu/com.aspose.slides/baseoverridethememanager/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Minden megvalósított interfész:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Alaposztály olyan osztályok számára, amelyek hozzáférést biztosítanak különböző típusú felülírt témákhoz.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Visszaadja a felülíró téma objektumát. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Visszaadja a felülíró téma objektumát. |
| [createThemeEffective()](#createThemeEffective--) | Visszaadja a téma objektumát. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Meghatározza, hogy az OverrideTheme felülírja-e az örökölt hatékony témát vagy sem. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Extra színsémát alkalmaz egy diára. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

Visszaadja a felülíró téma objektumát. Olvasás/írás [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Visszatérési érték:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

Visszaadja a felülíró téma objektumát. Olvasás/írás [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Visszatérési érték:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Visszaadja a téma objektumát.

**Visszatérési érték:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

Meghatározza, hogy az OverrideTheme felülírja-e az örökölt hatékony témát vagy sem. Az OverrideTheme felülírásának engedélyezéséhez használja az OverrideTheme.Init*() metódusokat. Az OverrideTheme felülírásának letiltásához használja az OverrideTheme.Clear() metódust. Csak olvasható bool.

**Visszatérési érték:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Extra színsémát alkalmaz egy diára.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | A [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) objektum. |