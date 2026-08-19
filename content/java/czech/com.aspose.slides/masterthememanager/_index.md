---
title: MasterThemeManager
second_title: Aspose.Slides pro Java API Reference
description: Poskytuje přístup k hlavnímu motivu prezentace.
type: docs
url: /cs/com.aspose.slides/masterthememanager/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

Poskytuje přístup k hlavnímu motivu prezentace.
## Metody

| Metoda | Popis |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Vrací objekt přepisujícího motivu. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | Vrací objekt přepisujícího motivu. |
| [createThemeEffective()](#createThemeEffective--) | Vrací objekt motivu. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Určuje, zda OverrideTheme přepisuje zděděný efektivní motiv (Presentation.MasterTheme), nebo ne. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | Určuje, zda OverrideTheme přepisuje zděděný efektivní motiv (Presentation.MasterTheme), nebo ne. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Použije další barevné schéma na snímek. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```


Vrací objekt přepisujícího motivu. Čtení/Zápis [IMasterTheme](../../com.aspose.slides/imastertheme).

**Vrací:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```


Vrací objekt přepisujícího motivu. Čtení/Zápis [IMasterTheme](../../com.aspose.slides/imastertheme).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


Vrací objekt motivu.

**Vrací:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```


Určuje, zda OverrideTheme přepisuje zděděný efektivní motiv (Presentation.MasterTheme), nebo ne. Čtení/Zápis boolean.

**Vrací:**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```


Určuje, zda OverrideTheme přepisuje zděděný efektivní motiv (Presentation.MasterTheme), nebo ne. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```


Použije další barevné schéma na snímek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) objekt. |