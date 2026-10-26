---
title: MasterThemeManager
second_title: Aspose.Slides voor Android via Java API-referentie
description: Biedt toegang tot het masterthema van de presentatie.
type: docs
url: /nl/com.aspose.slides/masterthememanager/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

Biedt toegang tot het master-thema van de presentatie.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Retourneert het overschrijfende thema-object. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | Retourneert het overschrijfende thema-object. |
| [createThemeEffective()](#createThemeEffective--) | Retourneert het thema-object. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Bepaalt of OverrideTheme het geërfde effectieve thema (Presentation.MasterTheme) overschrijft of niet. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | Bepaalt of OverrideTheme het geërfde effectieve thema (Presentation.MasterTheme) overschrijft of niet. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Past een extra kleurschema toe op een dia. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```

Retourneert het overschrijfende thema-object. Lezen/Schrijven [IMasterTheme](../../com.aspose.slides/imastertheme).

**Retour:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```

Retourneert het overschrijfende thema-object. Lezen/Schrijven [IMasterTheme](../../com.aspose.slides/imastertheme).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Retourneert het thema-object.

**Retour:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

Bepaalt of OverrideTheme het geërfde effectieve thema (Presentation.MasterTheme) overschrijft of niet. Lezen/Schrijven boolean.

**Retour:**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```

Bepaalt of OverrideTheme het geërfde effectieve thema (Presentation.MasterTheme) overschrijft of niet. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Past een extra kleurschema toe op een dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) object. |