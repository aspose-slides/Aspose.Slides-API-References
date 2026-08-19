---
title: BaseOverrideThemeManager
second_title: Aspose.Slides voor Java API Referentie
description: Basisklasse voor klassen die toegang bieden tot verschillende soorten overschreven thema's.
type: docs
url: /nl/com.aspose.slides/baseoverridethememanager/
---
**Erfenis:**
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
| [getOverrideTheme()](#getOverrideTheme--) | Retourneert het overschrijfende thema-object. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Retourneert het overschrijfende thema-object. |
| [createThemeEffective()](#createThemeEffective--) | Retourneert het thema-object. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Bepaalt of OverrideTheme het geërfde effectieve thema overschrijft of niet. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Past een extra kleurenpalet toe op een dia. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

Retourneert het overschrijfende thema-object. Lezen/schrijven [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Retour:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

Retourneert het overschrijfende thema-object. Lezen/schrijven [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

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

Bepaalt of OverrideTheme het geërfde effectieve thema overschrijft of niet. Om OverrideTheme in te schakelen voor overschrijven, gebruikt u de OverrideTheme.Init\*()-methoden. Om OverrideTheme uit te schakelen voor overschrijven, gebruikt u de OverrideTheme.Clear()-methode. Alleen-lezen boolean.

**Retour:**
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