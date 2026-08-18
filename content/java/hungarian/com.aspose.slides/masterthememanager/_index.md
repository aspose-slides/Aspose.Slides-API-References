---
title: MasterThemeManager
second_title: Aspose.Slides Java API referencia
description: Hozzáférést biztosít a prezentáció mester témához.
type: docs
url: /hu/com.aspose.slides/masterthememanager/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Minden megvalósított interfész:**
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

Hozzáférést biztosít a prezentáció mester témához.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Visszaadja a felülíró téma objektumot. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | Visszaadja a felülíró téma objektumot. |
| [createThemeEffective()](#createThemeEffective--) | Visszaadja a téma objektumot. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Megállapítja, hogy az OverrideTheme felülírja-e a örökölt hatékony témát (Presentation.MasterTheme), vagy sem. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | Megállapítja, hogy az OverrideTheme felülírja-e a örökölt hatékony témát (Presentation.MasterTheme), vagy sem. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Extra színsémát alkalmaz egy diára. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```


Visszaadja a felülíró téma objektumot. Olvasás/írás [IMasterTheme](../../com.aspose.slides/imastertheme).

**Visszatér:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```


Visszaadja a felülíró téma objektumot. Olvasás/írás [IMasterTheme](../../com.aspose.slides/imastertheme).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


Visszaadja a téma objektumot.

**Visszatér:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```


Megállapítja, hogy az OverrideTheme felülírja-e a örökölt hatékony témát (Presentation.MasterTheme), vagy sem. Olvasás/írás boolean.

**Visszatér:**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```


Megállapítja, hogy az OverrideTheme felülírja-e a örökölt hatékony témát (Presentation.MasterTheme), vagy sem. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```


Extra színsémát alkalmaz egy diára.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) objektum. |