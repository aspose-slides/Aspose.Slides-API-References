---
title: IOverrideThemeManager
second_title: Aspose.Slides voor Android via Java API-referentie
description: Biedt toegang tot verschillende soorten overschreven thema's.
type: docs
url: /nl/com.aspose.slides/ioverridethememanager/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

Biedt toegang tot verschillende soorten overschreven thema's.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Bepaalt of OverrideTheme een geërfd effectief thema overschrijft of niet. |
| [getOverrideTheme()](#getOverrideTheme--) | Retourneert het overschrijvende themobject. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Retourneert het overschrijvende themobject. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```


Bepaalt of OverrideTheme een geërfd effectief thema overschrijft of niet. Om OverrideTheme voor overschrijven in te schakelen, gebruik de OverrideTheme.Init\*() methoden. Om OverrideTheme van overschrijven uit te schakelen, gebruik de OverrideTheme.Clear() methode. Alleen-lezen boolean.

**Retourneert:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```


Retourneert het overschrijvende themobject. Lees/Schrijf [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Retourneert:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```


Retourneert het overschrijvende themobject. Lees/Schrijf [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |