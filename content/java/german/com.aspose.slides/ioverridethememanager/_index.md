---
title: IOverrideThemeManager
second_title: Aspose.Slides für Java API-Referenz
description: Stellt Zugriff auf verschiedene Arten von überschriebenen Themes bereit.
type: docs
url: /de/com.aspose.slides/ioverridethememanager/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

Stellt Zugriff auf verschiedene Arten von überschriebenen Themes bereit.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Bestimmt, ob OverrideTheme das geerbte effektive Theme überschreibt oder nicht. |
| [getOverrideTheme()](#getOverrideTheme--) | Gibt das überlagernde Theme-Objekt zurück. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Gibt das überlagernde Theme-Objekt zurück. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

Bestimmt, ob OverrideTheme das geerbte effektive Theme überschreibt oder nicht. Um OverrideTheme für das Überschreiben zu aktivieren, verwenden Sie die OverrideTheme.Init*()-Methoden. Um OverrideTheme vom Überschreiben zu deaktivieren, verwenden Sie die OverrideTheme.Clear()-Methode. Nur-Lese Boolean.

**Rückgabewert:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

Gibt das überlagernde Theme-Objekt zurück. Lese-/Schreib [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Rückgabewert:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

Gibt das überlagernde Theme-Objekt zurück. Lese-/Schreib [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |