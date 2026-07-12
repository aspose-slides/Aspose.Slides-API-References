---
title: BaseOverrideThemeManager
second_title: Aspose.Slides für Android über Java API Referenz
description: Basisklasse für Klassen, die Zugriff auf verschiedene Arten von überschriebenen Themes bieten.
type: docs
url: /de/com.aspose.slides/baseoverridethememanager/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Basisklasse für Klassen, die Zugriff auf verschiedene Arten von überschriebenen Themes bieten.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Returns the overriding theme object. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Returns the overriding theme object. |
| [createThemeEffective()](#createThemeEffective--) | Returns the theme object. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Determines whether OverrideTheme overrides inherited effective theme or not. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Applies extra color scheme to a slide. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

Gibt das überschreibende Theme-Objekt zurück. Lese/Schreib [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Rückgabe:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

Gibt das überschreibende Theme-Objekt zurück. Lese/Schreib [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Gibt das Theme-Objekt zurück.

**Rückgabe:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

Bestimmt, ob OverrideTheme das geerbte effektive Theme überschreibt oder nicht. Um OverrideTheme zum Überschreiben zu aktivieren, verwenden Sie die Methoden OverrideTheme.Init*(). Um OverrideTheme vom Überschreiben zu deaktivieren, verwenden Sie die Methode OverrideTheme.Clear(). Nur-Lese boolean.

**Rückgabe:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Wendet ein zusätzliches Farbschema auf eine Folie an.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | Das [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)-Objekt. |