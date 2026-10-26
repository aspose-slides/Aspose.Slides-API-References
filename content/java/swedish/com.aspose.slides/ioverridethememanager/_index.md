---
title: IOverrideThemeManager
second_title: Aspose.Slides för Java API-referens
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
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Bestämmer om OverrideTheme åsidosätter ärvt effektivt tema eller inte. |
| [getOverrideTheme()](#getOverrideTheme--) | Returnerar det överskrivna temaobjektet. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Returnerar det överskrivna temaobjektet. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

Bestämmer om OverrideTheme åsidosätter ärvt effektivt tema eller inte. För att aktivera OverrideTheme för överskrivning, använd metoderna OverrideTheme.Init*(). För att inaktivera OverrideTheme från överskrivning, använd metoden OverrideTheme.Clear(). Skrivskyddad boolean.

**Returnerar:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

Returnerar det överskrivna temaobjektet. Läs/skriv [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Returnerar:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

Returnerar det överskrivna temaobjektet. Läs/skriv [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |