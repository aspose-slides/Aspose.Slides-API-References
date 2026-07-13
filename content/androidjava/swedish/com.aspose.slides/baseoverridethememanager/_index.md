---
title: BaseOverrideThemeManager
second_title: Aspose.Slides för Android via Java API-referens
description: Basisklass för klasser som ger åtkomst till olika typer av överskrivna teman.
type: docs
url: /sv/com.aspose.slides/baseoverridethememanager/
---
**Arv:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Basklass för klasser som ger åtkomst till olika typer av överskrivna teman.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Returnerar det överskrivna temapobjektet. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Returnerar det överskrivna temapobjektet. |
| [createThemeEffective()](#createThemeEffective--) | Returnerar temapobjektet. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Avgör om OverrideTheme överskriver ärvt effektivt tema eller inte. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Tillämpar extra färgschema på en bild. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```


Returnerar det överskrivande temapobjektet. Läs/skriv [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Returnerar:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```


Returnerar det överskrivande temapobjektet. Läs/skriv [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


Returnerar temapobjektet.

**Returnerar:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```


Avgör om OverrideTheme överskriver ärvt effektivt tema eller inte. För att aktivera OverrideTheme för överskrivning, använd OverrideTheme.Init\*()-metoderna. För att inaktivera OverrideTheme från överskrivning, använd OverrideTheme.Clear()-metoden. Endast läsning boolean.

**Returnerar:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```


Tillämpar extra färgschema på en bild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | Objektet [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme). |