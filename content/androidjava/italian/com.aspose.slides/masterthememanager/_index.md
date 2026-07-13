---
title: MasterThemeManager
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Fornisce l'accesso al tema master della presentazione.
type: docs
url: /it/com.aspose.slides/masterthememanager/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

Fornisce l'accesso al tema master della presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Restituisce l'oggetto tema di sovrascrittura. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | Restituisce l'oggetto tema di sovrascrittura. |
| [createThemeEffective()](#createThemeEffective--) | Restituisce l'oggetto tema. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Determina se OverrideTheme sovrascrive il tema efficace ereditato (Presentation.MasterTheme) o meno. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | Determina se OverrideTheme sovrascrive il tema efficace ereditato (Presentation.MasterTheme) o meno. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Applica uno schema di colore extra a una diapositiva. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```


Restituisce l'oggetto tema di sovrascrittura. Lettura/Scrittura [IMasterTheme](../../com.aspose.slides/imastertheme).

**Restituisce:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```


Restituisce l'oggetto tema di sovrascrittura. Lettura/Scrittura [IMasterTheme](../../com.aspose.slides/imastertheme).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


Restituisce l'oggetto tema.

**Restituisce:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```


Determina se OverrideTheme sovrascrive il tema efficace ereditato (Presentation.MasterTheme) o meno. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```


Determina se OverrideTheme sovrascrive il tema efficace ereditato (Presentation.MasterTheme) o meno. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```


Applica uno schema di colore extra a una diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) object. |