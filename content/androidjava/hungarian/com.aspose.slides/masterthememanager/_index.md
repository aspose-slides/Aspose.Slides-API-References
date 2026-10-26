---
title: MasterThemeManager
second_title: Aspose.Slides Androidhoz Java API referenciája
description: Hozzáférést biztosít a prezentáció mester témájához.
type: docs
url: /hu/com.aspose.slides/masterthememanager/
---
**Öröklődés:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Minden megvalósított interfész:**
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

Hozzáférést biztosít a prezentáció mester témájához.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Visszaadja a felülbíráló téma objektumát. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | Visszaadja a felülbíráló téma objektumát. |
| [createThemeEffective()](#createThemeEffective--) | Visszaadja a téma objektumát. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Megállapítja, hogy az OverrideTheme felülbírálja-e az örökölt hatékony témát (Presentation.MasterTheme), vagy sem. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | Megállapítja, hogy az OverrideTheme felülbírálja-e az örökölt hatékony témát (Presentation.MasterTheme), vagy sem. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Alkalmaz egy extra színsémát a diára. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```


Visszaadja a felülbíráló téma objektumát. Olvasás/írás [IMasterTheme](../../com.aspose.slides/imastertheme).

**Visszatérési érték:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```


Visszaadja a felülbíráló téma objektumát. Olvasás/írás [IMasterTheme](../../com.aspose.slides/imastertheme).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |

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


Megállapítja, hogy az OverrideTheme felülbírálja-e az örökölt hatékony témát (Presentation.MasterTheme), vagy sem. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```


Megállapítja, hogy az OverrideTheme felülbírálja-e az örökölt hatékony témát (Presentation.MasterTheme), vagy sem. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```


Alkalmaz egy extra színsémát a diára.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) object. |