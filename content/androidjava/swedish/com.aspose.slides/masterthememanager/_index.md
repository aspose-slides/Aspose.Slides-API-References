---
title: MasterThemeManager
second_title: Aspose.Slides för Android via Java API-referens
description: Tillhandahåller åtkomst till presentationens huvudtema.
type: docs
url: /sv/com.aspose.slides/masterthememanager/
---
**Arv:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

Tillhandahåller åtkomst till presentationens huvudtema.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Returnerar det åsidosättande temobjektet. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | Returnerar det åsidosättande temobjektet. |
| [createThemeEffective()](#createThemeEffective--) | Returnerar temobjektet. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Avgör om OverrideTheme åsidosätter ärvt effektivt tema (Presentation.MasterTheme) eller inte. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | Avgör om OverrideTheme åsidosätter ärvt effektivt tema (Presentation.MasterTheme) eller inte. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Tillämpar extra färgschema på en bild. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```

Returnerar det åsidosättande temobjektet. Läs/skriv [IMasterTheme](../../com.aspose.slides/imastertheme).

**Returnerar:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```

Returnerar det åsidosättande temobjektet. Läs/skriv [IMasterTheme](../../com.aspose.slides/imastertheme).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Returnerar temobjektet.

**Returnerar:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

Avgör om OverrideTheme åsidosätter ärvt effektivt tema (Presentation.MasterTheme) eller inte. Läs/skriv boolean.

**Returnerar:**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```

Avgör om OverrideTheme åsidosätter ärvt effektivt tema (Presentation.MasterTheme) eller inte. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Tillämpar extra färgschema på en bild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) objekt. |