---
title: MasterThemeManager
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt Zugriff auf das Master-Design der Präsentation bereit.
type: docs
url: /de/com.aspose.slides/masterthememanager/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

Stellt Zugriff auf das Master-Design der Präsentation bereit.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Gibt das überschreibende Design-Objekt zurück. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | Gibt das überschreibende Design-Objekt zurück. |
| [createThemeEffective()](#createThemeEffective--) | Gibt das Design-Objekt zurück. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Bestimmt, ob OverrideTheme das vererbte wirksame Design (Presentation.MasterTheme) überschreibt oder nicht. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | Bestimmt, ob OverrideTheme das vererbte wirksame Design (Presentation.MasterTheme) überschreibt oder nicht. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Wendet ein zusätzliches Farbschema auf eine Folie an. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```


Gibt das überschreibende Design-Objekt zurück. Lesen/Schreiben [IMasterTheme](../../com.aspose.slides/imastertheme).

**Rückgabe:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```


Gibt das überschreibende Design-Objekt zurück. Lesen/Schreiben [IMasterTheme](../../com.aspose.slides/imastertheme).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


Gibt das Design-Objekt zurück.

**Rückgabe:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```


Bestimmt, ob OverrideTheme das vererbte wirksame Design (Presentation.MasterTheme) überschreibt oder nicht. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```


Bestimmt, ob OverrideTheme das vererbte wirksame Design (Presentation.MasterTheme) überschreibt oder nicht. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```


Wendet ein zusätzliches Farbschema auf eine Folie an.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) object. |