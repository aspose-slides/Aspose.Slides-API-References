---
title: BaseOverrideThemeManager
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Alaposztály azokhoz az osztályokhoz, amelyek hozzáférést biztosítanak a különböző típusú felülírt témákhoz.
type: docs
url: /hu/com.aspose.slides/baseoverridethememanager/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**All Implemented Interfaces:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Az alaposztály azokhoz az osztályokhoz, amelyek hozzáférést biztosítanak a különböző típusú felülírt témákhoz.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Visszatér a felülíró téma objektummal. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Visszatér a felülíró téma objektummal. |
| [createThemeEffective()](#createThemeEffective--) | Visszatér a téma objektummal. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Meghatározza, hogy az OverrideTheme felülírja-e a örökölt hatékony témát vagy sem. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Kiegészítő színsémát alkalmaz egy diára. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```


Visszatér a felülíró téma objektummal. Olvasási/írási [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Visszatér:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```


Visszatér a felülíró téma objektummal. Olvasási/írási [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


Visszatér a téma objektummal.

**Visszatér:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```


Meghatározza, hogy az OverrideTheme felülírja-e a örökölt hatékony témát vagy sem. Az OverrideTheme engedélyezéséhez felülíráshoz használja az OverrideTheme.Init\*() metódusokat. Az OverrideTheme felülírásának letiltásához használja az OverrideTheme.Clear() metódust. Csak olvasható bool típusú.

**Visszatér:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```


Kiegészítő színsémát alkalmaz egy diára.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | A [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) objektum. |