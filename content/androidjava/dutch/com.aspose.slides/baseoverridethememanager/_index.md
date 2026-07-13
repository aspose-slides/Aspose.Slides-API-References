---
title: BaseOverrideThemeManager
second_title: Aspose.Slides voor Android via Java API-referentie
description: Basisklasse voor klassen die toegang bieden tot verschillende soorten overschreven thema's.
type: docs
url: /nl/com.aspose.slides/baseoverridethememanager/
---
**Erfelijkheid:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Basisklasse voor klassen die toegang bieden tot verschillende soorten overschreven thema's.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Retourneert het overschrijfende themaobject. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Retourneert het overschrijfende themaobject. |
| [createThemeEffective()](#createThemeEffective--) | Retourneert het themaobject. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Bepaalt of OverrideTheme de geërfde effectieve thema overschrijft of niet. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Past een extra kleurenpalet toe op een dia. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

Retourneert het overschrijfende themaobject. Lezen/Schrijven [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Retourneert:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

Retourneert het overschrijfende themaobject. Lezen/Schrijven [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Retourneert het themaobject.

**Retourneert:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

Bepaalt of OverrideTheme de geërfde effectieve thema overschrijft of niet. Om OverrideTheme in te schakelen voor het overschrijven, gebruik OverrideTheme.Init*() methoden. Om OverrideTheme uit te schakelen voor het overschrijven, gebruik OverrideTheme.Clear() methode. Alleen-lezen boolean.

**Retourneert:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Past een extra kleurenpalet toe op een dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | Het [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) object. |