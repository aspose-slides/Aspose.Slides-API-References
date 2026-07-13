---
title: IOverrideThemeManager
second_title: Aspose.Slides för Android via Java API-referens
description: Tillhandahåller åtkomst till olika typer av överskrivna teman.
type: docs
url: /sv/com.aspose.slides/ioverridethememanager/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

Tillhandahåller åtkomst till olika typer av överskrivna teman.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Avgör om OverrideTheme åsidosätter ärvt effektivt tema eller inte. |
| [getOverrideTheme()](#getOverrideTheme--) | Returnerar det överskrivande temaattributet. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Returnerar det överskrivande temaattributet. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

Avgör om OverrideTheme åsidosätter ärvt effektivt tema eller inte. För att aktivera OverrideTheme för överskrivning använd OverrideTheme.Init\*() metoderna. För att inaktivera OverrideTheme från överskrivning använd OverrideTheme.Clear() metod. Skrivskyddad boolesk.

**Returnerar:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

Returnerar det överskrivande temaattributet. Läs/skriv [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Returnerar:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

Returnerar det överskrivande temaattributet. Läs/skriv [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |